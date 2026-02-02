# PRODIGY_ML_01
Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.   Dataset : - https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview
This project implements an end-to-end **Linear Regression** model to predict house prices using **all available features** from the Kaggle *House Prices – Advanced Regression Techniques* dataset.  
The workflow includes data preprocessing, feature encoding, model training, evaluation, visualization, and model persistence.

---

## 📊 Dataset
- **Source:** Kaggle – House Prices: Advanced Regression Techniques  
- **Link:** https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data  
- **Files Used:**
  - `train.csv` – training dataset with target variable
  - `test.csv` – test dataset for predictions

---

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Joblib

---

## 🧠 Machine Learning Approach

### ✔ Model Used
- **Linear Regression**

### ✔ Features
- All numerical and categorical features (79 total)

### ✔ Preprocessing
- Missing value handling (median / most frequent)
- One-Hot Encoding for categorical variables
- Feature scaling using StandardScaler
- Pipeline-based implementation to avoid data leakage

---

## 🔁 Project Workflow
1. Data loading and exploration
2. Feature-target separation
3. Identification of numerical and categorical columns
4. Data preprocessing using pipelines
5. Model training using Linear Regression
6. Model evaluation using RMSE and R² score
7. Visualization of results
8. Saving the trained model using Joblib

---

## 📈 Model Evaluation
- **Metric Used:**  
  - Root Mean Squared Error (RMSE)  
  - R² Score

> Note: Linear Regression provides a baseline model. More complex models may improve performance.

---

## 🖼️ Visualizations
Example outputs generated during EDA and evaluation:

- Actual vs Predicted House Prices
- Correlation Heatmap
- Feature Distributions

Images are stored in the `visuals/` directory.

---

## 📂 Project Structure

