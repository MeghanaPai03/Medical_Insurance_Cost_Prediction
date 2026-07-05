# 🏥 Medical Insurance Cost Prediction

## 📌 Project Overview

Medical insurance companies need to estimate healthcare costs based on customer information such as age, BMI, smoking status, number of children, and region. Accurate prediction of medical insurance charges helps insurers assess financial risk and determine appropriate premiums.

This project develops and compares multiple machine learning regression models to predict medical insurance charges and selects the best-performing model based on evaluation metrics.

---

## 🎯 Business Problem

Healthcare expenses vary significantly across individuals. Predicting medical insurance charges can help insurance providers:

- Estimate future medical expenses
- Assess customer risk
- Support premium pricing
- Improve financial planning

---

## 📂 Dataset

The dataset contains **1,338 customer records** with the following features:

Age, Sex, BMI, Children, Smoker, Region, Charges 

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- Google Colab

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Data exploration
- Missing value analysis
- Duplicate check
- Statistical summary
- Age distribution
- Gender distribution
- BMI distribution
- Children distribution
- Smoker distribution
- Region distribution

---

## 🤖 Machine Learning Models

Three regression models were trained and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|-------|------:|------:|------:|
| Linear Regression | 4267.21 | 6191.69 | 0.7447 |
| Decision Tree | 3367.69 | 6870.84 | 0.6857 |
| **Random Forest** | **2795.39** | **4947.95** | **0.8370** |

### Best Model

Random Forest Regressor achieved the highest R² Score and the lowest prediction errors, making it the best-performing model for predicting insurance charges.

---

## 🔍 Feature Importance

Random Forest feature importance analysis was performed to identify the variables that contribute most to predicting insurance charges.

---

## 📉 Residual Analysis

Residual analysis was performed to evaluate prediction errors and assess model performance.

---

## 💻 Predictive System

A predictive system was developed that accepts user inputs:

- Age
- Gender
- BMI
- Number of Children
- Smoking Status
- Region

and estimates the expected medical insurance charges using the trained Random Forest model.

---

## 🚀 Future Improvements

- Hyperparameter tuning
- One-Hot Encoding for Region
- Web application deployment using Streamlit
- Model optimization with GridSearchCV

---

## 📌 Conclusion

This project demonstrates an end-to-end machine learning workflow for predicting medical insurance charges. After comparing multiple regression models, Random Forest Regressor achieved the best predictive performance with an R² Score of approximately **0.84**. The project showcases data preprocessing, exploratory data analysis, model evaluation, comparison, and deployment-ready model serialization.
