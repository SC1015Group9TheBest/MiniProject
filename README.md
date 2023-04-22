# SC1015 Mini Project: Student Alcohol Consumption

## About The Project

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which explores and analyses [The Student Alcohol Consumption Dataset](https://www.kaggle.com/datasets/uciml/student-alcohol-consumption). For detailed walkthrough, please view the source code in order from:

1. [Data Cleaning](https://github.com/SC1015Group9TheBest/MiniProject/blob/main/1.%20Data%20Extraction%20and%20Cleaning.ipynb)
3. [Data Visualisation and EDA](https://github.com/SC1015Group9TheBest/MiniProject/blob/main/2.%20Data%20Visualization%20and%20EDA.ipynb)
4. [Decision Tree Classifier](https://github.com/SC1015Group9TheBest/MiniProject/blob/main/3.%20Decision%20Tree%20Classifier.ipynb)
5. [Hypothesis Testing](https://github.com/SC1015Group9TheBest/MiniProject/blob/main/4.%20Hypothesis%20Testing.ipynb)

## Problem Definition

1. Can we predict whether a student will pass or fail both subjects based on their attributes?
2. Are there any significant differences in students' condition, study habit data and students' grades between students who attend Gabriel Pereira school and those who attend Mousinho da Silveira school?

## Models Used

1. Decision Tree Classifier
2. Hypothesis Testing using t-test

## Conclusion

- Studytime and Pedu have weak positive correlation to grades. On the other hand, traveltime and failures have weak negative correlation to grades.
- There is no strong correlation between alcohol consumption and grades.
- Generally, there is an increase in median Math and Portuguese grades for students who study more.
- To predict students' pass/fail status, MG2 is the most important feature in making this prediction.
- Students who attend Gabriel Pereira school and students who attend Mousinho da Silveira school have the same grades for Maths but different grades for Portuguese.
- Gabriel Pereira students typically spend more time studying than their Mousinho da Silva counterparts, which corresponds to GP students attaining higher PG3 grades.

## What did we learn from this project?

- Data Cleaning: pd.merge, df.rename, df.drop_duplicates
- Hypothesis testing: t-test, scipy.stats.fisher_exact
- Decision Tree Classifier: feature_importances_
- Data Presenting: Presenting data clearly

## Contributors

- @JopatB / Jonathan Patrick Budihardjo - EDA, Hypothesis Testing, Decision Tree Classifier
- @apriliakeziaa / Kezia Aprilia Sanjaya - Data Visualization, EDA 
- @MaiNguyenTrucLinh / Mai Nguyen Truc Linh - Data Extraction, Data Cleaning, Hypothesis Testing

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
- [How feature importance is calculated in Decision Trees? with example](https://medium.com/data-science-in-your-pocket/how-feature-importance-is-calculated-in-decision-trees-with-example-699dc13fc078)
- [scipy.stats.fisher_exact](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.fisher_exact.html)
