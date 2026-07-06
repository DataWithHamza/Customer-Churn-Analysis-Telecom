# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.

In this project, I performed an end-to-end data analytics workflow to identify the major factors influencing customer churn in a telecom company. The project includes data cleaning, exploratory data analysis (EDA), SQL-based analysis, and an interactive Power BI dashboard to provide business insights and recommendations.

---

## 🎯 Business Problem

The telecom company is experiencing customer churn and wants to understand:

- Why are customers leaving?
- Which customers are most likely to churn?
- What factors contribute the most to churn?
- What strategies can improve customer retention?

---

## 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- Power BI
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographics, subscription details, services, billing information, tenure, and churn status.

Key columns include:

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Tech Support
- Contract
- Payment Method
- Monthly Charges
- Total Charges
- Churn

---

# 📈 Project Workflow

## 1. Data Cleaning

- Loaded the dataset
- Identified missing values
- Removed records with missing Total Charges
- Converted Total Charges to numeric
- Checked duplicates
- Saved cleaned dataset

---

## 2. Exploratory Data Analysis (EDA)

Performed analysis on:

- Customer churn distribution
- Gender vs churn
- Contract type vs churn
- Monthly charges vs churn
- Tenure vs churn
- Internet service vs churn
- Online security vs churn
- Tech support vs churn
- Payment method vs churn
- Correlation analysis

---

## 3. SQL Analysis

Used SQL to answer business questions including:

- Total customers
- Churned customers
- Churn rate
- Average monthly charges

---

## 4. Power BI Dashboard

Designed an executive dashboard to visualize:

- Total customers
- Churned customers
- Churn rate
- Average monthly charges
- Average tenure
- Churn by contract type
- Customer churn distribution
- Business insights

---

# 📊 Dashboard

![Dashboard](images/dashboard.png)

---

# 🔍 Key Insights

- Month-to-month customers have the highest churn rate.
- Customers with shorter tenure are significantly more likely to leave.
- Customers paying higher monthly charges are more likely to churn.
- Customers without Tech Support or Online Security show higher churn.
- Gender has minimal impact on customer churn.

---

# 💡 Business Recommendations

- Encourage customers to switch to long-term contracts through discounts and loyalty programs.
- Improve customer onboarding during the early months of service.
- Bundle Tech Support and Online Security with internet plans.
- Review pricing strategies for customers paying high monthly charges.
- Develop targeted retention campaigns for high-risk customers.

---

# 📁 Project Structure

```
Customer-Churn-Analysis-Telecom
│
├── data
├── notebooks
├── dashboard
├── images
├── README.md
├── requirements.txt
```

---

# 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/DataWithHamza/Customer-Churn-Analysis-Telecom.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Open the Jupyter notebooks.

4. Open the Power BI dashboard (.pbix).

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Analysis
- Exploratory Data Analysis
- SQL Queries
- Data Visualization
- Business Analytics
- Dashboard Design
- Business Storytelling

---

# 👨‍💻 Author

**Hamza**

Aspiring Data Analyst | Python | SQL | Power BI
