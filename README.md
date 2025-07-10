# Diabetes Prediction using Linear Regression

This project implements a simple **Linear Regression model** to predict diabetes (binary outcome) using the **Pima Indians Diabetes Dataset**.

## 📁 Dataset
- The dataset was read from CSV containing features like Glucose, Blood Pressure, Age, etc.

## 🧹 Preprocessing Steps
1. Replaced all zero values (except for 'Pregnancies' and 'Outcome') with the column mean.
2. Replaced the first row's Glucose value with the maximum value in the column.
3. Replaced the Glucose values for rows with the **minimum age** with the **minimum glucose** value.

## 🧠 Model
- Used **LinearRegression** from `sklearn.linear_model`.
- The model was trained on 80% of the dataset and tested on 20%.
- Predictions were rounded to 0 or 1 to suit binary classification.

## 📊 Evaluation Metrics

| Metric        | Value        |
|---------------|--------------|
| Accuracy      | 0.76         |
| Precision     | 0.73         |
| Recall        | 0.53         |
| F1 Score      | 0.61         |
| Confusion Matrix | [[354, 42], [104, 115]] |

## ✅ Key Libraries
- `pandas`, `numpy`
- `sklearn.model_selection.train_test_split`
- `sklearn.linear_model.LinearRegression`
- `sklearn.metrics`

## 📎 Report
See the full lab report (./213002158-CSE312-221D13-LabReport01-LinearRegression.pdf)

---

## 🔖 Author
**Md Ashik Mia**  
ID: 213002158  
Course: CSE312 (221D13)  
Green University of Bangladesh
