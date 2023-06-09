# SC1015-Student-Alcohol-Consumption

## About this Project
This mini project for SC1015 (Introduction to Data Science & Artificial Intelligence) will focus on alcohol consumption in students from [Student Alcohol Consumption Database](https://www.kaggle.com/datasets/uciml/student-alcohol-consumption?resource=download).

## Walkthrough
The portion contains the source code for our entire analysis of the database

1. [Data Extraction & Cleaning](https://github.com/EpitaxyInfinity/SC1015-Alcohol-Consumption/blob/main/Data%20Cleaning.ipynb)
2. [Exploratory Data Analysis](https://github.com/EpitaxyInfinity/SC1015-Alcohol-Consumption/blob/main/Exploratory%20Data%20Analysis.ipynb)
3. [Linear Regression](https://github.com/EpitaxyInfinity/SC1015-Alcohol-Consumption/blob/main/Linear%20Regression.ipynb)
4. [Requirements for running the Notebook](https://github.com/EpitaxyInfinity/SC1015-Alcohol-Consumption/blob/main/requirements.txt)

## Contributors
- Liu Xinyi - Data Analysis, Conclusion
- Sarah Soon Hui En @yuusuno - Presentation Slides, Data Preparation, Data Analysis
- Lim Jun Wei Ruben @EpitaxyInfinity - Data Preparation, Project Presentation

## Problem Definition
1. How does alcohol consumption influence the grades of students?
2. Can we predict grades based on a few attributes?

### Variables Used in Dataset:
1. school (student's school)
2. sex - student's sex
3. age - student's age
4. address - student's home address type
5. famsize - family size
6. Pstatus - parent's cohabitation status
7. Medu - mother's education
8. Fedu - father's education
9. traveltime - home to school travel time
10. studytime - weekly study time
11. famrel - quality of family relationships
12. freetime - free time after school
13. goout - going out with friends
14. Dalc - workday alcohol consumption
15. Walc - weekend alcohol consumption
16. health - current health status
17. absences - number of school absences
18. G1 - first period grade
19. G2 - second period grade
20. G3 - final grade

## Models Used
1. Linear Regression
2. Multiple Linear Regression

## Conclusion
- Alcohol consumption has a small effect on students’ grades
- Other factors like study time play an equal or more significant part to determining academic performance
- High correlation of father and mother’s education also implies that the students’ family background can also heavily influence academic performance

## What did we learn from this project?
- The use of multiple linear regression model
- How to filter out significant variables to use for model building

## References
- <https://www.kaggle.com/datasets/uciml/student-alcohol-consumption?resource=download>
- <https://pandas.pydata.org/docs/reference/api/pandas.get_dummies.html>
- <https://www.analyticsvidhya.com/blog/2021/05/multiple-linear-regression-using-python-and-scikit-learn/>
- <https://datatofish.com/multiple-linear-regression-python/>
