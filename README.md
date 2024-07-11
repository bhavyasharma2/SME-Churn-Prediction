# SME Churn Prediction

## Overview

This project focuses on predicting the churn of Small and Medium-sized Enterprises (SMEs) using various features. The analysis and model development were carried out in a Jupyter Notebook.

## Notebook Content

The Jupyter Notebook includes the following sections:

### Data Loading and Preprocessing

- Loaded client data and price data using Pandas.
- Converted date columns to datetime objects.
- Calculated the tenure of customers in years.
- Dropped unnecessary columns from the data.

### Data Exploration

- Displayed the first few rows of the datasets to understand their structure.
- Checked the shape of the datasets and summary statistics.
- Visualized data distributions and relationships among features.

### Feature Engineering

- Created new features based on existing data to enhance model performance.

### Model Building and Evaluation

- Separated the target variable (churn) from the independent variables.
- Split the data into training and test sets.
- Built a Random Forest Classifier to predict churn.
- Evaluated the model using accuracy, precision, recall, F1 score, and ROC AUC score.

### Results

- Achieved the following metrics on the test set:
  - **Accuracy:** 90.38%
  - **Precision:** 82.60%
  - **Recall:** 51.91%
  - **F1 Score:** 97.68%
  - **ROC AUC Score:** 52.53%

## Acknowledgements

- Special thanks to BCG and the Forage platform for providing the dataset and project framework.
