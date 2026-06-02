📌 Customer Churn Prediction & Retention Analytics Platform
🧠 Project Overview

Customer churn is a critical business problem in subscription-based and e-commerce businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project builds an end-to-end analytics and machine learning system to:

Predict customer churn probability
Identify key churn drivers
Segment customers by risk and value
Estimate revenue at risk
Provide actionable retention strategies

The solution combines Python, SQL, Machine Learning, and Business Intelligence (Power BI) to deliver a complete analytics pipeline.

🎯 Business Problem

E-commerce companies lose significant revenue due to customer churn. The goal is to:

Identify customers likely to churn
Understand why they churn
Quantify revenue risk
Prioritize retention efforts effectively
📊 Dataset Overview
Total Records: 5,630 customers
Domain: E-commerce Customer Behavior
Target Variable: Churn (0 = No, 1 = Yes)
Key Features:
Tenure
Complaint history
Cashback amount
Order behavior
Customer value metrics
Engagement behavior
Demographics
🛠️ Tech Stack

Programming & Analysis

Python (Pandas, NumPy)
SQL (SQLite)
Jupyter Notebook

Machine Learning

Scikit-learn
Logistic Regression
Random Forest Classifier

Visualization

Matplotlib
Seaborn
Power BI

Version Control

Git & GitHub
🔄 Project Workflow
1️⃣ Data Cleaning & Preprocessing
Handled missing values
Encoded categorical variables
Feature engineering (Value segmentation, retention scoring)
2️⃣ Exploratory Data Analysis (EDA)

Key insights:

Churn distribution analysis
Tenure vs churn relationship
Complaint impact on churn
Revenue contribution analysis
3️⃣ SQL Analytics Layer

Advanced SQL queries were used for:

Customer segmentation analysis
Revenue at risk estimation
Churn rate by customer groups
Window functions for ranking customers
4️⃣ Machine Learning Models
Models Used:
Logistic Regression (Baseline)
Random Forest Classifier (Final Model)
📈 Model Performance
Logistic Regression:
Accuracy: 88.9%
ROC-AUC: 0.885
Recall: 51.6%
Random Forest (Best Model):
Accuracy: 97.8%
Precision: 99.4%
Recall: 87.4%
F1 Score: 93.0%
ROC-AUC: 0.999
🧠 Key Business Insights
🔹 Top Churn Drivers
Tenure (most important factor)
Cashback amount
Complaint history
Customer value
Order behavior
🔹 Business Impact Insights
Customers with complaints are ~3x more likely to churn
High-value customers contribute major revenue risk
Early-tenure customers show highest churn probability
💰 Revenue at Risk
High Value Segment contributes the largest revenue at risk (~63%)
~840 high-risk customers identified
Significant opportunity for retention optimization
🚨 Retention Strategy Engine

A Retention Priority Score was created:

Combines churn probability + customer value

This allows businesses to:

Prioritize high-value at-risk customers
Optimize retention budget allocation
Focus on high ROI interventions
📊 SQL Highlights
Churn segmentation using GROUP BY
Revenue analysis using CTEs
Customer ranking using Window Functions
Risk segmentation analysis
📉 Key Visual Insights (Power BI)

Dashboard includes:

Churn Overview KPIs
Customer Segmentation
Revenue at Risk
High-risk customer ranking
Feature importance insights
📌 Project Structure
Customer-Churn-Prediction/
│
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── images/
├── customer_churn.db
├── requirements.txt
├── README.md
🚀 Business Value

This project demonstrates how data science can directly support business decisions:

Improves customer retention strategy
Identifies high-risk customers early
Reduces revenue loss
Optimizes marketing spend
Enables data-driven decision making
📌 Key Takeaway

Instead of only predicting churn, this project builds a full retention intelligence system that prioritizes customers based on risk and business value.

👨‍💻 Author

Vaishu
Final Year AI Student
Specialization: Data Analytics, Machine Learning, Business Intelligence
