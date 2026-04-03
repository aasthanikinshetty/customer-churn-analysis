# Customer Churn Analysis & Revenue Impact Project

## Business Problem
A telecom company is experiencing customer churn, resulting in significant
revenue loss. This project aims to:
- Identify customers at high risk of churning
- Quantify the revenue at risk (in ₹)
- Segment customers by value and risk
- Recommend targeted retention strategies

## Tools Used
Python, Pandas, Scikit-learn, Power BI

## Dataset
IBM Telco Customer Churn Dataset (via Kaggle)
```

This alone shows business maturity. Most people skip it entirely.

---

## Step 2 — Project Folder Structure

Set this up in VS Code right now:
```
churn_project/
│
├── data/
│   └── telco_churn.csv        ← raw dataset goes here
│
├── notebooks/
│   └── 01_data_cleaning.ipynb
│   └── 02_eda.ipynb
│   └── 03_model.ipynb
│
├── outputs/
│   └── cleaned_data.csv       ← saved after cleaning
│
├── dashboard/
│   └── churn_dashboard.pbix   ← Power BI file later
│
└── README.md