# 📊 Customer Churn Prediction Project
This project aims to predict customer churn using machine learning models, specifically Random Forest and Logistic Regression. The analysis involves data preprocessing, exploratory data analysis (EDA), and evaluating model performance using various metrics.

# 🚀 Project Overview
Customer churn is a critical problem for businesses, especially in subscription-based industries. This project uses a dataset containing customer information to predict whether a customer is likely to churn or not. The goal is to help businesses identify potential churners early and take proactive measures to retain them.

# 📁 Dataset
The dataset used in this project contains the following key features:

Demographics: Information such as senior citizen status.
Services: Types of services the customer has signed up for (e.g., Internet service, contract type).
Account Information: Tenure, monthly charges, and total charges.
Target Variable: Churn (Yes/No) indicating whether the customer churned.
# 🛠️ Technologies Used
Python: Core programming language
Pandas, NumPy: Data manipulation
Matplotlib, Seaborn, Plotly: Data visualization
Scikit-Learn: Machine learning models and evaluation metrics
XGBoost: Additional classification model
Missingno: Visualization for missing data handling
# 📊 Steps Involved
1. Data Preprocessing
Handled missing values in TotalCharges.
Dropped irrelevant columns (e.g., customerID).
Encoded categorical variables using LabelEncoder.
Standardized numerical features (tenure, MonthlyCharges, TotalCharges).
2. Exploratory Data Analysis (EDA)
Visualized distributions of key numerical features.
Analyzed correlations to identify important predictors.
Explored churn rates based on different customer segments.
3. Model Building
Implemented:
Random Forest Classifier
Logistic Regression
Split data into 70% training and 30% testing sets.
4. Model Evaluation
Metrics used:
Accuracy
Recall
Precision
F1-Score
ROC Curves
Compared model performance to determine the best approach.
# 📈 Results
Feature Importance: Identified key features affecting churn, such as MonthlyCharges and Contract type.
Model Comparison: Random Forest provided a balance between accuracy and interpretability, while Logistic Regression offered a simpler model for quick insights.
