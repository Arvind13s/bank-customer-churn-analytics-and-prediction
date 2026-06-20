# 🏦 Bank Customer Churn Analytics & Prediction System

An end-to-end Data Analytics and Machine Learning project that analyzes bank customer behavior, identifies churn patterns, and predicts customer attrition using classification models and interactive Power BI dashboards.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges in the banking industry. Retaining existing customers is significantly more cost-effective than acquiring new ones. This project aims to:

* Analyze customer demographics and financial attributes
* Identify factors contributing to customer churn
* Segment customers based on behavior and characteristics
* Build and evaluate machine learning models for churn prediction
* Develop interactive dashboards for business stakeholders

The project combines **Python, Machine Learning, and Power BI** to deliver actionable business insights and predictive analytics.

---

## 🎯 Objectives

* Perform exploratory data analysis (EDA) on customer data
* Understand churn patterns across countries, age groups, and products
* Engineer features for machine learning
* Train and compare multiple classification algorithms
* Optimize model performance using threshold tuning
* Build interactive dashboards for executive reporting and model interpretation

---

## 📊 Dataset Information

The dataset contains information about **10,000 bank customers**, including:

* Credit Score
* Country
* Gender
* Age
* Tenure
* Account Balance
* Number of Products
* Credit Card Ownership
* Active Membership Status
* Estimated Salary
* Churn Status (Target Variable)

### Target Variable

* **0 → No Churn**
* **1 → Churn**

---

## 🛠️ Tech Stack

### Programming & Analytics

* Python
* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn
* Power BI

### Machine Learning

* Scikit-Learn
* XGBoost

### Development Tools

* Jupyter Notebook
* VS Code
* Git
* GitHub

---

## 📂 Project Structure

```text
Bank-Customer-Churn-Analytics/
│
├── data/
│   ├── BankChurners.csv
│   ├── cleaned_bank_churn.csv
│   ├── model_metrics.csv
│   └── confusion_metrix.csv
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   ├── features.ipynb
│   ├── shap_analysis.ipynb
│   └── model_building.ipynb
│
├── dashboard/
│   └── Bank_Customer_Churn_Analytics.pbix
│
├── screenshots/
│   ├── executive_overview.png
│   ├── customer_segmentation.png
│   └── prediction_model.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📈 Exploratory Data Analysis

The analysis focused on understanding customer behavior and identifying churn drivers.

### Key Findings

* Overall churn rate: **20.37%**
* Germany exhibited the highest churn rate among all countries.
* Customers aged **51–60 years** showed significantly higher churn.
* Customers owning **3–4 products** were more likely to churn.
* Female customers showed slightly higher churn compared to male customers.
* Active members had substantially lower churn rates than inactive customers.

---

# 🤖 Machine Learning Pipeline

## Data Preparation

* Data cleaning and preprocessing
* Feature engineering
* Label encoding
* Stratified train-test split
* Handling class imbalance
* Threshold optimization

---

## Models Implemented

### 1. Logistic Regression

Used as the baseline classification model.

### 2. Random Forest Classifier

Used for capturing nonlinear relationships and feature interactions.

### 3. XGBoost Classifier

Used as the final model due to superior predictive performance.

---

# 🏆 Final Model Performance (Tuned XGBoost)

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 85.10% |
| Precision | 63.73% |
| Recall    | 62.16% |
| F1 Score  | 62.94% |
| ROC-AUC   | 86.67% |
| PR-AUC    | 71.33% |

---

# 📉 Confusion Matrix

| Actual \ Predicted | Churn | No Churn |
| ------------------ | ----- | -------- |
| Churn              | 253   | 154      |
| No Churn           | 144   | 1449     |

---

# 📊 Power BI Dashboard

The project includes a **3-page interactive dashboard**.

---

## Page 1 – Executive Overview

Provides high-level business insights:

* Total Customers
* Churn Rate
* Active Members
* Average Balance
* Churn by Country
* Churn by Age Group
* Churn by Gender
* Churn by Number of Products
* Interactive Filters

---

## Page 2 – Customer Segmentation

Analyzes customer demographics and financial distributions:

* Average Credit Score
* Average Salary
* Average Tenure
* Average Age
* Customers by Country
* Age Distribution
* Credit Score Distribution
* Balance Distribution
* Gender Distribution
* Interactive Filters

---

## Page 3 – Churn Prediction Model Insights

Presents machine learning evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* PR-AUC
* Classification Metrics Comparison
* Confusion Matrix

---

# 💡 Business Insights

### Customer Retention Strategy

Customers aged **51–60 years** and inactive members should be prioritized for retention campaigns.

### Geographic Focus

Germany exhibited the highest customer churn and may require targeted intervention strategies.

### Product Optimization

Customers holding multiple products demonstrated higher churn tendencies, suggesting opportunities for product redesign and customer engagement initiatives.

### Predictive Monitoring

The trained XGBoost model can help identify high-risk customers proactively and enable early intervention strategies.

---

# 🚀 Future Improvements

* Deploy the model using FastAPI or Flask
* Create a real-time prediction application using Streamlit
* Implement model monitoring and retraining pipelines
* Integrate cloud deployment using AWS or Docker
* Develop explainable AI dashboards using SHAP values

---

# 📸 Dashboard Preview

### Executive Overview

![Executive Overview](  https://github.com/Arvind13s/bank-customer-churn-analytics-and-prediction/blob/main/screenshots/Page1.png)

### Customer Segmentation

![Customer Segmentation](https://github.com/Arvind13s/bank-customer-churn-analytics-and-prediction/blob/main/screenshots/Page2.png)

### Prediction Model Insights

![Prediction Model](https://github.com/Arvind13s/bank-customer-churn-analytics-and-prediction/blob/main/screenshots/Page3.png)

---

# 👨‍💻 Author

**Arvind Singh**
