# PRODIGY_ML_01
Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.   Dataset : - https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

# House Price Prediction using Linear Regression

## Project Overview
This project implements an end-to-end Linear Regression model to predict house prices using all available features from the Kaggle *House Prices – Advanced Regression Techniques* dataset.  
The workflow covers data preprocessing, feature encoding, model training, evaluation, visualization, and model saving.

---

## Dataset
- Source: Kaggle – House Prices: Advanced Regression Techniques  
- Link: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data  
- Files:
  - train.csv – training dataset
  - test.csv – test dataset

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Joblib

---

## Machine Learning Approach
- Model: Linear Regression
- Features: All numerical and categorical features (79 total)
- Preprocessing:
  - Missing value handling (median / most frequent)
  - One-hot encoding for categorical features
  - Feature scaling using StandardScaler
  - Pipeline-based implementation to avoid data leakage

---

## Workflow
1. Load and explore the dataset
2. Separate features and target variable
3. Identify numerical and categorical columns
4. Apply preprocessing using pipelines
5. Train Linear Regression model
6. Evaluate model using RMSE and R² score
7. Visualize predictions and feature relationships
8. Save trained model using Joblib

---

## Model Evaluation
- Metrics used:
  - Root Mean Squared Error (RMSE)
  - R² Score

Note: Linear Regression is used as a baseline model for this dataset.

---

## Visualizations
Key visualizations generated during analysis:
- Actual vs Predicted house prices
- Correlation heatmap
- Feature distributions

All images are stored in the `visuals/` directory.

---

## Project Structure

oject Structure

