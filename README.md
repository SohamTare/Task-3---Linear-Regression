# Linear-Regression  (29-05-2025)
Linear Regression task 

# 📊 Linear Regression Project - Task 3

This project demonstrates the implementation of **Simple and Multiple Linear Regression** using the `scikit-learn` library. It covers the full machine learning pipeline including preprocessing, model training, evaluation, and visualization.

---

## 🔍 Objective

To understand and implement:
- Simple and Multiple Linear Regression
- Preprocessing for regression tasks
- Model evaluation using MAE, MSE, and R² score
- Interpretation of regression coefficients and visualization

---

## 🗂️ Dataset

The dataset used contains both numerical and categorical features. One column is selected as the **target variable**, which is to be predicted.

---

## ✅ Tasks Completed

1. **Import and Preprocess Data**
   - Loaded the dataset using pandas
   - Handled missing values (mean/median imputation)
   - Converted categorical variables to numeric using encoding
   - Standardized numerical features for consistent scale

2. **Train-Test Split**
   - Used `train_test_split()` to split the data (80/20 ratio)

3. **Model Training**
   - Used `LinearRegression()` from `sklearn.linear_model` to train the model

4. **Model Evaluation**
   - Evaluated using **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R² Score**

5. **Visualization**
   - Plotted the regression line
   - Interpreted coefficients and residuals

---

## 📈 Results

The model was evaluated on the test set using:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **R² Score:** Indicates the proportion of variance explained

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 🧠 Key Learnings

- Importance of preprocessing before model training
- Difference between simple and multiple linear regression
- How to interpret coefficients
- Metrics for evaluating regression performance


