# SME Churn Prediction

## Overview
This project focuses on predicting the churn of Small and Medium-sized Enterprises (SMEs) using machine learning techniques. The primary goal is to help businesses proactively identify at-risk customers and implement strategies to improve retention.

## Problem Statement
Customer churn is a significant challenge for businesses, directly affecting revenue and growth. For this project, the client, a leading energy company, experiences a churn rate of approximately **10%**. Existing retention strategies may not effectively address all the factors influencing churn, making predictive analytics crucial for decision-making.

## Key Objectives
- **Data-Driven Insights:** Understand key drivers influencing SME churn.
- **Predictive Modeling:** Develop an accurate churn prediction model.
- **Strategic Recommendations:** Provide actionable insights for reducing churn and improving customer retention.

## Notebook Content
The Jupyter Notebook contains the following sections:

### 1. Data Loading and Preprocessing
- Loaded **client data** and **price data** using Pandas.
- Converted date columns to datetime format.
- Calculated customer **tenure** in years.
- Removed unnecessary columns to improve model efficiency.

### 2. Data Exploration
- Examined dataset structure and distributions.
- Visualized feature relationships using data visualization techniques.
- Identified key characteristics of customers prone to churn.

### 3. Feature Engineering
- Created **new features** to enhance model performance.
- Extracted insights from energy consumption trends, pricing, and net margins.

### 4. Model Building and Evaluation
- Defined **churn** as the target variable.
- Split data into **training and test sets**.
- Built a **Random Forest Classifier** to predict customer churn.
- Evaluated model performance using:
  - **Accuracy:** 90.38%
  - **Precision:** 82.60%
  - **Recall:** 51.91%
  - **F1 Score:** 97.68%
  - **ROC AUC Score:** 52.53%

## Conclusion / Executive Summary

### **Situation**
- Customer churn presents a financial risk, impacting profitability and market competitiveness.
- The client, an energy provider, experiences **10% churn** among SMEs.

### **Complication**
- Current retention strategies **do not effectively address** the diverse factors leading to churn.
- Without a proactive solution, **revenue loss and declining customer loyalty** are imminent.

### **Model Solution**
- The **main churn drivers** are:
  - **Yearly consumption**
  - **Forecasted consumption**
  - **Net margin**
- **Price sensitivity is not the primary driver** of churn, suggesting a need for refined retention strategies.
- A **Random Forest Classifier** was implemented, achieving **90% accuracy** in predicting at-risk customers.

### **Recommendation**
- **Offer targeted discounts** only to **high-value** customers with a **high churn probability**, optimizing retention efforts while minimizing revenue leakage.

### **Impact**
- The solution allows the company to:
  - **Identify at-risk customers early**
  - **Optimize intervention strategies**
  - **Enhance profitability and market positioning**

### **Tools and Technologies**

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Machine Learning (Random Forest Classifier)

## Acknowledgements

- Special thanks to BCG and the Forage platform for providing the dataset and project framework.
