# SC1015 Mini Project: Student Alcohol Consumption

## About The Project

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which explores and analyses [The Student Alcohol Consumption Dataset](https://www.kaggle.com/datasets/uciml/student-alcohol-consumption). For detailed walkthrough, please view the source code in order from:

1. [Data Cleaning]()
3. [Data Visualisation and EDA]()
4. [Decision Tree Classifier]()
5. [Hypothesis Testing]()

## Problem Definition

1. Can we predict whether a student will pass or fail both subjects based on their attributes?
2. Are there any significant differences in students' condition, study habit data and students' grades between students who attend Gabriel Pereira school and those who attend Mousinho da Silveira school?

## Models Used

1. Decision Tree Classifier
2. Hypothesis Testing using t-test

## Conclusion

- Popularity and budget have low linear correlation value with ratings (watch out for bandwagons 🤣)
- Popularity of the casts and crews have higher linear correlation value with ratings
- Resampling imbalanced data improved model performance especially on the minority class
- Logistic Regression did not perform well with non-linearly correlated variables
- Neural Networks along with SMOTEENN resampling method consistently did well in predicting good movies after 100 training attempts (around 72% accuracy, 70% recall)
- Yes, it is possible to predict if a movie is good with acceptable amount of accuracy and recall

## What did we learn from this project?

- Data Cleaning: pd.merge, df.rename, df.drop_duplicates
- Data Visualization: swarm plot
- Hypothesis testing: t-test
- Decision Tree Classifier: feature_importances_

## Contributors

- @JopatB - EDA, Hypothesis Testing, Decision Tree Classifier
- @apriliakeziaa - Data Visualization, EDA 
- @MaiNguyenTrucLinh - Data Extraction, Data Cleaning, Hypothesis Testing

## References

- [pandas.DataFrame.fillna](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.fillna.html)
- [pandas merging user guide](https://pandas.pydata.org/docs/user_guide/merging.html#)
- [What is the Secret of Academic Success?](https://www.kaggle.com/code/hely333/what-is-the-secret-of-academic-success)
- [Does Alcohol Affect Success?](https://www.kaggle.com/code/kanncaa1/does-alcohol-affect-success)
- [pandas.DataFrame.drop_duplicates](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop_duplicates.html)
- [Pandas Merge DataFrames with Shared Column Fillna in Left with Right](https://stackoverflow.com/questions/56842140/pandas-merge-dataframes-with-shared-column-fillna-in-left-with-right)
- [scipy.stats.ttest_ind](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html)
- [pandas.DataFrame.dropna](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.dropna.html)
- [Changing a column of 'yes'/'no' to 1/0 in a Pandas DataFrame](https://stackoverflow.com/questions/40901770/is-there-a-simple-way-to-change-a-column-of-yes-no-to-1-0-in-a-pandas-dataframe)
- [Gradient Boosting Regression - Feature Importance](https://github.com/Eligijus112/gradient-boosting/blob/master/regression/feature_importance.ipynb)
