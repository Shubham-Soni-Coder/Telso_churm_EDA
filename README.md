# 📊 Telco Customer Churn Analysis

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of a Telecommunications Customer Churn dataset. The primary objective is to clean, process, and analyze customer data to uncover patterns and factors influencing customer retention and churn.

Through data visualization and statistical analysis, this project provides actionable insights into customer behavior and highlights key business areas that impact customer loyalty.

---

## 🎯 Objectives

- Understand customer churn patterns.
- Identify factors contributing to customer attrition.
- Perform data cleaning and preprocessing.
- Generate meaningful visualizations.
- Extract business insights from customer data.

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Development Environment
- Jupyter Notebook

---

## 📂 Dataset Information

The dataset contains:

- **7,043 customer records**
- **21 features**
- Customer demographic information
- Service subscriptions
- Contract details
- Billing information
- Churn status

---

## 🔧 Data Cleaning & Preprocessing

Several preprocessing steps were performed to ensure data quality and consistency:

### 1. Initial Data Inspection
- Loaded the dataset using Pandas.
- Examined data types, dimensions, and feature information.

### 2. Handling Missing Values
- Identified blank values in the `TotalCharges` column.
- Replaced missing values with `0`.
- Converted the column to a numeric (`float`) datatype.

### 3. Data Quality Validation
- Checked for missing values.
- Checked for duplicate records.
- Verified dataset integrity.

### Results:
- ✅ Missing Values: 0
- ✅ Duplicate Records: 0

### 4. Feature Transformation
The `SeniorCitizen` column was transformed:

| Original | Converted |
|-----------|-----------|
| 0 | No |
| 1 | Yes |

This improved readability during visualization and analysis.

---

## 📈 Exploratory Data Analysis

The project includes several visualizations to understand customer behavior and churn trends.

### Overall Customer Churn

A combination of count plots and pie charts revealed:

- **26.54% of customers churned**
- **73.46% of customers were retained**

This indicates that approximately one out of every four customers leaves the service.

---

### Customer Tenure Analysis

A histogram was used to analyze customer tenure against churn status.

#### Key Insight:
- New customers show a significantly higher churn rate.
- Long-term customers are more likely to remain loyal.

---

### Contract Type Analysis

Customer churn was analyzed across different contract types.

#### Key Insight:
- Month-to-month contracts experience the highest churn rate.
- One-year and two-year contracts have significantly lower churn rates.

This suggests that longer commitments improve customer retention.

---

### Senior Citizen Analysis

A stacked bar chart was used to compare churn behavior between senior and non-senior customers.

#### Key Insight:
- Senior citizens have a higher proportional churn rate compared to non-senior customers.

---

### Service-Based Analysis

Multiple visualizations were generated to study the relationship between churn and service usage.

Services analyzed include:

- Phone Service
- Internet Service
- Multiple Lines
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies

#### Key Insight:
Customers without value-added services such as:

- Tech Support
- Online Security
- Device Protection

show a noticeably higher churn tendency.

---

## 📊 Key Business Insights

### Insight 1
Customer churn rate is approximately **26.54%**, indicating a significant retention challenge.

### Insight 2
Customers with **month-to-month contracts** are at the highest risk of churn.

### Insight 3
Long-tenure customers demonstrate stronger loyalty and lower churn probability.

### Insight 4
Senior citizens exhibit relatively higher churn rates.

### Insight 5
Customers lacking additional support and security services are more likely to leave.

---

## 📁 Project Structure

```text
Telco_Churn_Analysis/
│
├── Telso_churm_data.csv
├── main.ipynb
├── analysis_summary.pdf
├── README.md
└── images/
```

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/Shubham-Soni-Coder/Telso_churm_EDA.git
```

### Navigate to the Project Directory

```bash
cd Telso_churm_EDA
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
main.ipynb
```

and run all cells.

---

## 📷 Visualizations Included

- Churn Distribution
- Customer Tenure Analysis
- Contract Type Analysis
- Senior Citizen Analysis
- Service-Based Churn Analysis
- Correlation Heatmaps

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Business Insight Generation
- Data Visualization
- Customer Churn Analysis
- Pandas & Seaborn Workflows

---

## 👨‍💻 Author

### Shubham Soni

Aspiring Data Analyst | Python Developer | Machine Learning Enthusiast

GitHub:
https://github.com/Shubham-Soni-Coder

LinkedIn:
https://www.linkedin.com/in/shubham-soni-a99285309/
---

⭐ If you found this project useful, consider giving the repository a star.
