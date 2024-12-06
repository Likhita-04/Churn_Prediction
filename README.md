# Churn_Prediction

Introduction
Customer churn is a critical issue for many industries, where businesses lose clients to competitors or dissatisfaction. This project focuses on building machine learning models to predict customer churn, helping businesses identify at-risk customers and take proactive measures.

The project workflow involves:
Data Preprocessing: Cleaning and transforming raw data.

Exploratory Data Analysis (EDA): Understanding key relationships between features and churn.

Feature Engineering: Enhancing the dataset with new features.

Modeling: Training several machine learning models.

Model Evaluation: Comparing model performance using various metrics.

Insights and Interpretation: Understanding the key drivers of churn based on model results.

Techniques Used
Exploratory Data Analysis (EDA) Visualization: Histograms, bar plots, and correlation heatmaps revealed patterns in customer behavior, such as: Higher churn rates for customers with month-to-month contracts. A strong correlation between high monthly charges and churn.

Feature Engineering New Features: Created tenure categories to help capture the effect of customer loyalty. One-hot Encoding: Categorical features like contract type, payment method, and internet service were converted into numerical values for model input. Scaling: Numerical features such as monthly charges were scaled to improve model performance

Modeling Several machine learning models were applied:

Logistic Regression

SVM

Decision Tree

Random Forest

Contract Type: Customers with month-to-month contracts were far more likely to churn.

Monthly Charges: Higher monthly charges led to increased churn likelihood.

Customer Tenure: Newer customers had a higher chance of churning.

Paperless Billing: Slightly higher churn was seen among customers using paperless billing, possibly due to less frequent interaction with the company.
