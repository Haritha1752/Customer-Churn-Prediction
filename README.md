# Telco Customer Churn Prediction

## Project Overview
This project aims to analyze and predict customer churn in the telecommunications industry using various machine learning algorithms. The dataset used for this project is the "Telco Customer Churn" dataset, available on Kaggle.

The objective is to identify customers who are at high risk of churning and develop effective retention strategies based on data insights.

## Table of Contents
- [Project Description](#Project-Description)
- [Data Description](Data-Description)
- [Exploratory Data Analysis (EDA)](Exploratory-Data-Analysis (EDA))
- [Data Preprocessing](Data-Preprocessing)
- [Model Building](Model-Building)
- [Evaluation Metrics](Evaluation-Metrics)
- [Key Insights](Key-Insights)
- [Conclusion](Conclusion)
- [References](References)
  
## Project Description
Customer churn is a critical issue in the telecommunications industry, as retaining customers is more cost-effective than acquiring new ones. This project aims to predict whether a customer is likely to churn using machine learning models, thus helping the company to take preemptive measures.

## Data Description
The dataset contains customer details like:

- **Demographics:** Gender, Senior Citizen status, Partner, Dependents
- **Services:** Phone service, Multiple lines, Internet service, Online security, Device protection, Tech support
- **Contracts:** Month-to-month, One year, Two year
- **Payment Methods:** Electronic check, Mailed check, Bank transfer, Credit card
- **Target Variable:** Churn (Yes/No)

## Exploratory Data Analysis (EDA)
Analysis of churn rates based on gender, payment methods, contract type, and tenure.
Visualizations like histograms, bar charts, and pie charts to understand the distribution of customer attributes.

## Data Preprocessing
#### Key steps in data preprocessing:

- Handling missing values and outliers
- Encoding categorical variables using One-Hot Encoding and Label Encoding
- Scaling numerical data using StandardScaler to normalize features
- Addressing class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)
  
## Model Building
#### Multiple machine learning models were implemented and evaluated:

- Random Forest
- Logistic Regression
- Decision Tree
- AdaBoost
- XGBoost
##### Hyperparameter tuning was conducted using GridSearchCV to find the optimal parameters for each model.

## Evaluation Metrics
#### Models were evaluated based on:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve
## Key Insights
- Customers with month-to-month contracts are more likely to churn.
- Higher monthly charges correlate with increased churn rates.
- Customers using fiber optic internet are more likely to churn than those using DSL.
- Absence of tech support and online security services also contribute to higher churn rates.
  
## Conclusion
The Random Forest and Logistic Regression models provided the best balance between precision and recall, making them suitable for predicting customer churn. These insights can be used to target at-risk customers and implement retention strategies.

## References
Telco Customer Churn dataset: Kaggle
