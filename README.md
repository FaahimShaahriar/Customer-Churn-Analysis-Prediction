**📊 Customer Churn Analysis Dashboard (Power BI + Python)**


This project provides an end-to-end analysis of customer churn using both Python (for data cleaning and machine learning) and Power BI (for interactive business reporting). The goal is to identify key factors contributing to churn and empower stakeholders with actionable insights.

📁 Project Overview
Dataset: Telco Customer Churn Dataset

Tools Used:

🐍 Python (Pandas, Scikit-learn, XGBoost)

📊 Power BI (DAX, cards, matrix, slicers)

📁 CSV for transferring cleaned data

🧠 Features & Workflow
🔸 Python:
Cleaned and preprocessed the dataset (handled nulls, converted dtypes, encoded categoricals)

Performed EDA (box plots, count plots, heatmaps)

Trained multiple models: Logistic Regression, Random Forest, XGBoost

Evaluated with accuracy and ROC-AUC metrics

Exported clean dataset for Power BI use

🔸 Power BI:
KPI Cards: Total Customers, Churned Customers, Churn Rate, Avg Monthly Charges, Avg Tenure

Breakdown Visuals:

Churn by Contract Type (bar chart)

Churn by Internet Service (stacked column)

Churn by Payment Method (donut chart)

Trend Analysis:

Churn Rate by Tenure (line chart with tenure bins)

Heatmap: Churn across Contract Type × Payment Method

Filters/Slicers:

Gender, Senior Citizen, Internet Service, Tenure Group

📈 Key Business Insights
📉 Customers on Month-to-Month contracts are far more likely to churn

💳 Those paying via Electronic Check have significantly higher churn

⏳ Long-tenure and Two-Year contracts reduce churn risk

🧭 Recommendations:

Incentivize long-term contracts

Improve experience for electronic check users
