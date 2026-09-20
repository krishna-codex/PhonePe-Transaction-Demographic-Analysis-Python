# 📱 PhonePe Transaction & Demographic Analysis — Python

> End-to-end Python analysis of PhonePe transaction, user, device, and demographic data across Indian states and districts to identify transaction trends, user behavior, device patterns, and demographic relationships.

---

## 📌 Project Overview

This project analyzes PhonePe transaction and demographic data using Python to understand digital payment trends across India.

The analysis covers:

* Transaction volumes
* Transaction values
* Registered users
* Device usage
* App engagement
* Population and demographic data
* State-level and district-level trends

The project also includes data cleaning, exploratory data analysis, visualization, correlation analysis, data reconciliation, and business recommendations.

---

## 🎯 Business Objectives

The main objectives of this project are to:

* Analyze transaction trends across Indian states and districts.
* Identify states and regions with high transaction activity.
* Understand registered-user and device-usage patterns.
* Study the relationship between population demographics and transaction volume.
* Identify data-quality and reconciliation gaps.
* Generate actionable insights for digital-payment adoption and user engagement.

---

## 📂 Dataset

The project uses multiple datasets containing transaction, user, device, and demographic information.

### Excel Sheets Used

The `PhonePe_Data.xlsx` file contains the following sheets:

| Sheet                    | Description                                      |
| ------------------------ | ------------------------------------------------ |
| `State_Txn and Users`    | State-level transaction and registered-user data |
| `State_TxnSplit`         | State-level transaction category information     |
| `State_DeviceData`       | Device usage and user information                |
| `District_Txn and Users` | District-level transaction and user data         |
| `District Demographics`  | District-level demographic information           |

A district-to-state mapping CSV is also included to support geographical analysis.

---

## 🧹 Data Preparation

The analysis includes the following data-preparation steps:

* Loading Excel and CSV files using Pandas.
* Standardizing column names.
* Removing unnecessary spaces from column names.
* Checking data consistency.
* Preparing datasets for state-level and district-level analysis.
* Combining transaction and demographic information for deeper analysis.
* Performing reconciliation between related datasets.

---

## 🔍 Analysis Performed

### 💳 Transaction Analysis

* State-wise transaction-volume analysis.
* Transaction amount and value analysis.
* Yearly and quarterly transaction trends.
* Identification of high-performing states.
* Analysis of transaction activity across districts.

### 👥 User Analysis

* Registered-user analysis across states.
* Comparison of registered users with population.
* Identification of digital-adoption patterns.
* Analysis of user engagement through app opens.

### 📱 Device Analysis

* Analysis of device usage across users.
* Identification of commonly used device brands.
* Comparison of device usage patterns across regions.

### 🗺️ Demographic Analysis

* District-level population analysis.
* Population density vs. transaction-volume analysis.
* Analysis of demographic relationships with digital-payment activity.
* Correlation analysis between demographic variables and transactions.

### 🔎 Data Quality Analysis

* State-level vs. district-level reconciliation.
* Identification of potential data gaps.
* Identification of inconsistencies between datasets.
* Validation of aggregated values.

---

## 📊 Key Findings

### 1. Highest Transaction Volume

Karnataka recorded the highest total transaction volume in the available state-level data:

**2,981,044,533 transactions**

---

### 2. Highest Weighted Average Transaction Value

Ladakh recorded the highest weighted average transaction value (ATV):

**₹3,514.15**

---

### 3. Population Density & Transaction Volume

The Pearson correlation between district population density and transaction volume was:

**0.4188**

This indicates a **moderate positive relationship** between population density and transaction activity in the analyzed dataset.

---

### 4. App Engagement

App opens can be analyzed alongside transaction activity to understand changes in user engagement and identify potential opportunities for improving digital-payment adoption.

---

### 5. Data Reconciliation

Regular reconciliation between district-level and state-level datasets can help identify data-quality gaps and improve the accuracy of analytical reporting.

---

## 💡 Business Recommendations

Based on the analysis, the following actions can support digital-payment growth and reporting:

* Strengthen digital-payment infrastructure in high-potential regions.
* Use state and district-level trends to design localized campaigns.
* Monitor app opens alongside transaction activity to understand user engagement.
* Perform regular district-to-state reconciliation to improve data quality.
* Automate reconciliation and reporting workflows for faster analysis.
* Use demographic indicators to identify regions requiring additional digital-payment adoption initiatives.

---

## 📸 Analysis Visualizations

### 📊 Transaction Trends

<img width="1189" height="590" alt="transaction-trends" src="https://github.com/user-attachments/assets/2b66986a-74d2-499a-a07a-5a46f01cce91" />


State-level transaction analysis highlighting changes in transaction volume and transaction amount over time.

---

### 📈 Population Density vs Transaction Volume

<img width="788" height="590" alt="density-vs-transaction-volume" src="https://github.com/user-attachments/assets/cd338e3d-ef3f-48a4-b848-43b5d375c607" />



Correlation analysis examining the relationship between district population density and transaction volume.

---

### 📱 Registered Users to Population Ratio

<img width="1390" height="590" alt="registered-users-population-ratio" src="https://github.com/user-attachments/assets/c1b48645-463b-4ccf-af3f-f6fe13813f8f" />


State-level comparison of registered users relative to population to understand digital-payment adoption patterns.

---

## 🛠️ Tools & Skills

### Programming & Libraries

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

### Analysis & Visualization

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Correlation Analysis
* Statistical Analysis
* Data Reconciliation
* Business Analysis

### Environment

* **Jupyter Notebook**

---

## 📓 Notebook Workflow

The Jupyter Notebook follows an end-to-end analytical workflow:

```text
Data Loading
     ↓
Data Cleaning & Preparation
     ↓
Exploratory Data Analysis
     ↓
Transaction Analysis
     ↓
User & Device Analysis
     ↓
Demographic Analysis
     ↓
Correlation Analysis
     ↓
Data Reconciliation
     ↓
Visualization
     ↓
Business Insights & Recommendations
```

---

## 📂 Project Structure

```text
phonepe-data-analyst-project/
│
├── PhonePe_Data_Analyst_Project.ipynb
├── PhonePe_Data.xlsx
├── district_name_code_mapping.csv
├── README.md
│
└── screenshots/
    ├── transaction-trends.png
    ├── density-vs-transaction-volume.png
    └── registered-users-population-ratio.png
```

---

## 🚀 Key Skills Demonstrated

This project demonstrates practical skills in:

* Python for Data Analysis
* Pandas Data Manipulation
* NumPy
* Data Cleaning
* Exploratory Data Analysis
* Statistical Correlation
* Data Visualization
* Geographic/District-Level Analysis
* Data Reconciliation
* Business Insight Generation
* Translating Data into Actionable Recommendations
---

## 👨‍💻 Author

**Krishna Shrivastava**

Aspiring Data Analyst | Python | SQL | Power BI | Excel
