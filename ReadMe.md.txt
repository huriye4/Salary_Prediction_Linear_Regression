Salary Prediction of Baseball Players with Machine Learning

Overview

This project involves building a machine learning model to predict the salary of baseball players based on their seasonal and career statistics. The main objective is to use various regression models to assess the relationship between these statistics and the salary.

Table of Contents

1) Data Exploration and Preprocessing
2) Model Building and Evaluation
3)Results



Data Exploration and Preprocessing

Loading the Data:

A dataset containing 20 features (seasonal and career statistics of baseball players) and the target variable (salary) was loaded into the notebook.


Exploratory Data Analysis (EDA):

Conducted an initial exploration of the data to understand its structure, distribution, and relationships.
Identified and handled missing values if any.


Data Visualization:

Visualized the distribution of each variable.
Created visualizations to understand the relationships between features and the target variable.


Model Building and Evaluation

Simple Linear Regression:

Built a simple linear regression model to establish a baseline.
Used cross-validation to assess the performance of the model.

Multiple Linear Regression:

Built and evaluated a multiple linear regression model to explore more complex relationships between the features and the salary.
Used cross-validation to determine the model’s accuracy.

Ridge Regression:

Implemented Ridge Regression, a type of regularized linear regression, to assess its performance.
Cross-validated the model to measure its effectiveness.

Lasso Regression:

Implemented Lasso Regression to reduce the number of features and assess its impact on the model’s performance.
Cross-validated the model to determine its accuracy.

Elastic Net Regression:

Implemented Elastic Net Regression, combining Lasso and Ridge techniques.
Cross-validated the model and analyzed its performance.

Feel free to explore the implementation and findings in the notebook named SALARY PREDICTION OF BASEBALL PLAYERS WITH LINEAR REGRESSION