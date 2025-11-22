# Telco Customer Churn Prediction

This project predicts customer churn for a fictional telecommunications company using the IBM Telco Customer Churn dataset.

## Overview

The goal of this project is to:
- Explore the dataset and understand key drivers of churn.
- Build machine learning models to predict whether a customer will churn.
- Compare model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
- Identify important features that influence churn.

## Dataset

The dataset used is the **Telco Customer Churn** dataset (IBM sample data).  
It contains customer demographics, services subscribed, account information, and a churn label.

> Note: Due to licensing and file size, the raw CSV file is not stored in this repository.  
> You can download a similar dataset from Kaggle by searching for **"Telco Customer Churn"**.

## Project Structure

```text
telco-customer-churn-ml/
├─ data/
│   └─ telco_customer_churn.csv      # (not committed – add yourself)
├─ notebooks/
│   └─ 01_telco_churn_eda_and_model.ipynb
├─ models/
│   └─ telco_churn_rf_pipeline.joblib
├─ src/
│   └─ utils.py                      # optional helpers
├─ requirements.txt
└─ README.md
