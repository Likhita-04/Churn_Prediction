

# Churn Prediction

Customer churn is a critical issue across industries where businesses lose clients due to dissatisfaction or competition. This project aims to build machine learning models to predict customer churn, enabling businesses to identify at-risk customers and take proactive measures to retain them.

## Project Workflow
The project follows these steps:
1. **Data Preprocessing**: Cleaning and transforming raw data to prepare it for analysis.
2. **Exploratory Data Analysis (EDA)**: Gaining insights into customer behavior and identifying key relationships between features and churn.
3. **Feature Engineering**: Creating new features, encoding categorical variables, and scaling numerical data to improve model performance.
4. **Modeling**: Training several machine learning models to predict churn.
5. **Model Evaluation**: Comparing model performance using various metrics.
6. **Insights and Interpretation**: Understanding the key drivers of churn based on model results.

## Techniques Used

### Exploratory Data Analysis (EDA)
Visualizations such as histograms, bar plots, and correlation heatmaps revealed key patterns in customer behavior:
- Higher churn rates for customers with month-to-month contracts.
- A strong correlation between high monthly charges and churn.

### Feature Engineering
- **New Features**: Created tenure categories to capture the effect of customer loyalty.
- **One-hot Encoding**: Converted categorical features like contract type, payment method, and internet service into numerical values.
- **Scaling**: Scaled numerical features such as monthly charges to improve model performance.

### Machine Learning Models
Several machine learning models were applied, including:
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

## Key Insights
- **Contract Type**: Customers with month-to-month contracts were far more likely to churn.
- **Monthly Charges**: Higher monthly charges increased the likelihood of churn.
- **Customer Tenure**: Newer customers had a higher chance of churning.
- **Paperless Billing**: Slightly higher churn was observed among customers using paperless billing, possibly due to less frequent interaction with the company.

---

