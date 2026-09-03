# 📱 PhonePe Transaction & Demographic Analysis — Python

> End-to-end Python analysis of PhonePe transaction, user, device, and demographic data across Indian states and districts.

---

## 📌 Project Overview

This project analyzes PhonePe transaction and user data to uncover patterns in transaction activity, user behavior, device usage, and demographic characteristics across Indian states and districts.

The analysis combines multiple datasets from the supplied PhonePe workbook and uses Python for data loading, cleaning, transformation, exploratory analysis, visualization, data-quality validation, and insight generation.

---

## 🎯 Business Objectives

The analysis focuses on:

- Understanding transaction trends across states and districts
- Analyzing transaction value and transaction volume
- Examining user behavior and app engagement
- Understanding device usage patterns
- Exploring demographic relationships with transaction activity
- Identifying data-quality gaps through reconciliation checks
- Generating actionable business recommendations

---

## 📂 Dataset

The project uses data from the following areas:

- State-level transaction and user data
- State-level transaction split data
- State-level device data
- District-level transaction and user data
- District demographic data

The notebook loads these datasets directly from the PhonePe Excel workbook.

---

## 🧹 Data Preparation & Cleaning

Key preparation steps included:

- Loading multiple Excel sheets using Pandas
- Standardizing column names
- Inspecting dataset structure and data types
- Checking for missing values
- Preparing data for state- and district-level analysis
- Aggregating transaction and user metrics
- Creating derived analytical metrics
- Reconciling district-level data with state-level data to identify data-quality gaps

---

## 📊 Analysis Performed

### 1. Transaction Trend Analysis

Analyzed transaction volume and transaction value across states and over time to identify high-activity markets and changes in transaction behavior.

### 2. User & App Engagement Analysis

Examined registered users and app opens alongside transaction metrics to understand engagement and monetization patterns.

### 3. Device Usage Analysis

Analyzed device-related data to understand patterns in PhonePe usage across states.

### 4. Demographic Analysis

Explored relationships between district demographics and transaction activity, including population density and transaction volume.

### 5. Data Quality & Reconciliation

Performed district-to-state reconciliation checks to identify differences between aggregated district data and state-level reporting.

### 6. Business Insight Generation

Converted analytical findings into recommendations related to digital-payment infrastructure, localized campaigns, user engagement, and reporting quality.

---

## 🔍 Key Findings

- **Karnataka** recorded the highest total transaction volume in the available state-level data, with **2,981,044,533 transactions**.
- **Ladakh** recorded the highest weighted average transaction value (ATV) among states at **₹3,514.15**.
- The Pearson correlation between district population density and transaction volume was **0.4188**, indicating a moderate positive relationship.
- Transaction activity and app opens should be monitored together to understand changes in user engagement and monetization.
- Regular district-to-state reconciliation can help identify data-quality gaps before reporting.

---

## 💡 Business Recommendations

Based on the analysis:

- Use district-level transaction and population patterns to prioritize digital-payment infrastructure.
- Use localized campaigns in high-potential markets.
- Monitor app opens alongside transactions to detect engagement changes early.
- Regularly reconcile district and state datasets to improve reporting accuracy.
- Automate reconciliation checks in future reporting pipelines.

---

## 🛠️ Tools & Skills Demonstrated

### Python

- Python
- Pandas
- NumPy

### Data Analysis

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Aggregation
- GroupBy Analysis
- Correlation Analysis
- Data Quality Validation
- Trend Analysis
- Comparative Analysis

### Data Visualization

- Matplotlib
- Seaborn

---

## 📸 Analysis Visualizations

Visualizations from the notebook will be added to this section to provide a quick view of the analytical results.

---

## 📂 Project Structure

```text
phonepe-data-analyst-project/
│
├── PhonePe_Data_Analyst_Project.ipynb
├── PhonePe_Data.xlsx
├── district_name_code_mapping.csv
└── README.md
