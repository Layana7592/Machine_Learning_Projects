# Predict Salary Using Linear Regression

## Project Description
This project demonstrates **Simple Linear Regression** using Python to **predict employee salaries based on years of experience**.  
It includes **data exploration, visualization, model training, predictions, and evaluation metrics**.  
This project is ideal for **beginners learning machine learning** and linear regression concepts.

---

## Dataset
- The dataset used is `Salary_Data.csv`.
- It contains two columns:
  - `YearsExperience` – independent variable (X)  
  - `Salary` – dependent variable (Y)

---

## Libraries Used
- `numpy` – for numerical computations  
- `pandas` – for data manipulation  
- `matplotlib` – for data visualization  
- `scikit-learn` – for machine learning (Linear Regression, train-test split, metrics)

---

## Workflow / Steps
1. **Data Loading** – Import CSV using pandas.  
2. **Data Exploration** – View first & last rows, check for missing values, info summary.  
3. **X–Y Separation** – Divide dataset into features (X) and target (Y).  
4. **Train-Test Split** – Split data into training (70%) and testing (30%) sets.  
5. **Model Training** – Fit a Simple Linear Regression model on training data.  
6. **Prediction** – Predict salaries for test data and new input values.  
7. **Evaluation** – Compute performance metrics:  
   - Mean Absolute Error (MAE)  
   - Mean Absolute Percentage Error (MAPE)  
   - R² Score  
8. **Visualization** – Scatter plot of data and regression line.

---

## Results
- The trained model predicts salaries based on experience.  
- Provides a comparison table between **actual vs predicted values**.  
- Displays **model slope (coefficient) and intercept**.  
- Visualizes the regression line on top of the scatter plot.  

---


