# WPI-Deep-Learning-with-Advanced-Robotic-Perception--Week-4
- Evaluating the performance of a Binary classification

We will be using the Sonar dataset. This is a dataset that describes sonar chirp returns bouncing off different surfaces. The 60 input variables are the strength of the returns at different angles. It is a binary classication problem that requires a model to differentiate rocks from metal cylinders.
It is a well understood dataset. All of the variables are continuous and generally in the
range of 0 to 1. The output variable is a string M for mine and R for rock, which will need to be
converted to integers 1 and 0. The dataset contains 208 observations.

/Files/Week 4/Binary Classification/

- Evaluating the performance of a Multiclass classification

The iris flowers dataset. This dataset is well studied and is a good problem for practicing on neural networks because all of the 4 input variables are numeric and have the same scale in centimeters. Each instance describes the properties of an observed flower measurements and the output variable is specific iris species. The attributes for this dataset can be summarized as follows:
1. Sepal length in centimeters.
2. Sepal width in centimeters.
3. Petal length in centimeters.
4. Petal width in centimeters.
5. Class.
This is a multiclass classification problem, meaning that there are more than two classes to be predicted, in fact there are three flower species.

/Files/Week 4/Multiclass Classification/

- Evaluating the performance of a regression problem
The Boston house price dataset. The dataset describes properties of houses in Boston suburbs and is concerned with modeling the price of houses in those suburbs in thousands of dollars. As such, this is a regression predictive modeling problem. There are 13 input variables that describe the properties of a given Boston suburb.
The full list of attributes in this dataset are as follows:
1. CRIM: per capita crime rate by town.
2. ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS: proportion of non-retail business acres per town.
4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
5. NOX: nitric oxides concentration (parts per 10 million).
6. RM: average number of rooms per dwelling.
7. AGE: proportion of owner-occupied units built prior to 1940.
8. DIS: weighted distances to ve Boston employment centers.
9. RAD: index of accessibility to radial highways.
10. TAX: full-value property-tax rate per $10,000.
11. PTRATIO: pupil-teacher ratio by town.
12. B: 1000(Bk - 0:63)^2 where Bk is the proportion of blacks by town.
13. LSTAT: % lower status of the population.
14. MEDV: Median value of owner-occupied homes in $1000s.
This is a well studied problem in machine learning.

/Files/Week 4/Regression/
