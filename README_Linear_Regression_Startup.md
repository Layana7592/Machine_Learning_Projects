# Startup Profit Prediction Using Linear Regression with One-Hot Encoding

## Overview
This project analyzes the **50 Startups dataset** to predict **startup profits** based on investment in **R&D, Administration, and Marketing**, along with the **State**. It demonstrates **data preprocessing, one-hot encoding, linear regression modeling, and evaluation** of model performance.

## Dataset
- The dataset contains 50 observations of startups with the following columns:
  - **R&D Spend**: Investment in Research and Development
  - **Administration**: Investment in Administration
  - **Marketing Spend**: Investment in Marketing
  - **State**: Location of the startup
  - **Profit**: Startup profit (target variable)

- Dataset Source: [50_Startups.csv](https://raw.githubusercontent.com/arib168/data/main/50_Startups.csv)

## Steps Performed
1. **Importing Libraries**: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`.
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing distributions of features and target.
   - Checking relationships using scatter plots and regression plots.
   - State-wise startup count analysis (bar and pie charts).
3. **Data Preprocessing**:
   - Handling categorical variables using **One-Hot Encoding**.
   - Splitting dataset into **training and testing sets**.
4. **Modeling**:
   - Applying **Linear Regression** to predict profits.
5. **Evaluation**:
   - Metrics used: **MAE, MAPE, MSE, RMSE, R² Score**.
   - Visualizing predictions vs actual profits.


