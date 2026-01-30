# 📊 Customer Churn Prediction

## 🔹 Introduction
Customer churn prediction helps companies identify customers who are likely to stop using their service. This allows businesses to take preventive actions and improve customer retention.

## 🔹 Objective
To analyze customer data, identify churn patterns, and build machine learning models to predict which customers are at risk of leaving.

## 🔹 Dataset
A simulated telecom dataset of 2000 customers was used with features like:
* Tenure
* Monthly & Total Charges
* Contract Type
* Internet Service
* Tech Support
* Payment Method
* Senior Citizen

The target variable was **Churn (Yes/No)**.

## 🔹 Exploratory Data Analysis

EDA revealed that:
* Customers with **month-to-month contracts** churn more
* **Low tenure** customers are more likely to leave
* **High monthly charges** increase churn risk
* Lack of **tech support** is linked to higher churn

## 🔹 Models Used

Three classification models were applied:
* Logistic Regression
* Random Forest
* XGBoost

## 🔹 Evaluation Metrics

Models were evaluated using:
* **Accuracy**
* **Recall** (important to catch actual churners)
* **ROC-AUC**

## 🔹 Results
* Tree-based models (**Random Forest & XGBoost**) performed better than Logistic Regression
* These models captured complex churn patterns more effectively

## 🔹 Conclusion

The project shows how machine learning can help businesses predict customer churn and take proactive steps like offers, support improvements, and retention campaigns to reduce customer loss.
