Boston Housing Prices Analysis and Prediction
Introduction:
This notebook aims to provide insights and visualizations for the Boston housing prices dataset, clean the data, and apply several popular machine learning regression algorithms to predict housing prices. The performance of each model will be evaluated and compared.

About The Boston Housing Dataset:
The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. The following describes the dataset columns:
CRIM - per capita crime rate by town
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per 10,000 dollars
PTRATIO - pupil-teacher ratio by town
B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT - % lower status of the population
MEDV - Median value of owner-occupied homes in 1000 dollars's

Target Column:
In this dataset, the target column (the column we aim to predict using the other features) is MEDV (Median value of owner-occupied homes in 1000 dollars's). The goal of using this dataset is typically to develop a model that can estimate housing prices based on various influencing factors (features).
