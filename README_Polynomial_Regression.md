📌 Project Overview

This project demonstrates the difference between Simple Linear Regression and Polynomial Regression using a Temperature–Pressure dataset.
It helps understand how polynomial regression can model non-linear relationships, while linear regression is limited to straight-line predictions.

🗂 Dataset

The dataset contains two columns:

Temperature (X) – Independent variable

Pressure (Y) – Dependent variable

Example data:

Temperature	Pressure
1	30
2	35
3	50
4	80
5	130

The dataset is stored in poly.csv.

🧰 Steps Performed

Import Libraries: Pandas, NumPy, Matplotlib, Scikit-learn

Load Dataset: poly.csv

Data Preprocessing:

Removed unnecessary columns (sno)

Separated independent (X) and dependent (y) variables

Simple Linear Regression:

Trained linear regression model

Predicted values

Evaluated using MAPE

Visualized regression line

Polynomial Regression:

Transformed X using PolynomialFeatures(degree=3)

Trained linear model on polynomial features

Predicted values

Evaluated using MAPE

Visualized polynomial curve

Comparison: Created a table comparing actual, linear, and polynomial predictions

📊 Key Results

Linear regression fits a straight line but underfits non-linear data

Polynomial regression fits the curve better, reducing errors

MAPE comparison shows polynomial regression is more accurate

Visual plots clearly illustrate the difference

📈 Plots

Linear Regression Plot – Straight line vs actual data

Polynomial Regression Plot – Curve fitting actual data

📝 Conclusion

For non-linear relationships, polynomial regression is preferable.

Simple linear regression is suitable only when the relationship is approximately linear.

Polynomial regression may overfit if the degree is too high; degree=3 is often a good balance.

🔗 Colab Link

Open Notebook in Google Colab

https://colab.research.google.com/drive/1KXFprKJNhQk7FaE6_i-pbNQ842Nrrqf1?usp=sharing

🏷 Tags / Skills

Machine Learning Regression Polynomial Regression Linear Regression Python Scikit-learn Data Visualization
