# 🏦 Bank Customer Churn & Risk Analysis

## 📌 Project Overview

Customer churn is an important business problem for banks because losing existing customers can affect revenue and long-term customer relationships.

This project analyzes **10,000 bank customers** to understand customer churn patterns and identify customers with multiple churn-risk signals.

The analysis was performed using **Python and Pandas** for data preparation and feature engineering, followed by **Power BI and DAX** for interactive dashboarding and business analysis.

---

## 🎯 Business Objective

- Understand the overall customer churn rate.
- Identify customer segments with higher churn.
- Analyze churn based on age, geography, activity, credit score, and product usage.
- Create a rule-based customer risk scoring framework.
- Identify high-risk customers for retention analysis.
- Build an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Jupyter Notebook**
- **Power BI**
- **DAX**
- **CSV Dataset**

---

## 📊 Dataset

The dataset contains information about **10,000 bank customers**.

| Feature | Description |
|---|---|
| CustomerId | Unique customer identifier |
| CreditScore | Customer credit score |
| Geography | Customer location |
| Gender | Customer gender |
| Age | Customer age |
| Tenure | Years with the bank |
| Balance | Customer account balance |
| NumOfProducts | Number of bank products used |
| HasCrCard | Whether the customer has a credit card |
| IsActiveMember | Customer activity status |
| EstimatedSalary | Estimated customer salary |
| Exited | Customer churn indicator |
| Complain | Whether the customer submitted a complaint |
| Satisfaction Score | Customer satisfaction score |
| Card Type | Type of card held |
| Point Earned | Customer points |

`Exited = 1` represents a churned customer, while `Exited = 0` represents a retained customer.

---

## 🧹 Data Preparation

Python and Pandas were used for data preparation and feature engineering.

Created features:

- **AgeGroup**
- **CreditBand**
- **BalanceSegment**
- **ActivityStatus**
- **RiskScore**
- **RiskLevel**

The dataset was also checked for missing values, duplicates, data consistency, and appropriate data types.

---

## ⚠️ Customer Risk Scoring

A **rule-based risk scoring framework** was developed using multiple customer attributes.

Risk signals included:

- Inactive membership
- Age 40 or above
- Credit score below 600
- Having only 1 product
- Having 3 or more products
- Zero account balance

Customers were grouped into:

- 🟢 **Low Risk**
- 🟡 **Medium Risk**
- 🔴 **High Risk**

> The risk score is a rule-based analytical framework for customer segmentation. It is not a machine learning prediction model.

---

## 📈 Key Findings

- **Total Customers:** 10,000
- **Churn Rate:** 20.38%
- **High-Risk Customers:** 843
- **High-Risk Churn Rate:** 56.11%
- **High-Risk Churned Customers:** 473

### Age-Based Churn

| Age Group | Churn Rate |
|---|---:|
| Under 30 | 7.56% |
| 50–60 | 56.04% |

The analysis also examined churn across geography, customer activity, credit bands, number of products, and balance segments.

---

## 📊 Power BI Dashboard

The final dashboard contains **2 pages**.

### Page 1 — Churn Overview

- Total Customers
- Churned Customers
- Churn Rate
- Active Customers
- Average Balance
- Churn by Geography
- Churn by Age Group
- Churn by Activity Status
- Churn by Number of Products
- Churn by Credit Band
- Churn by Balance Segment

### Page 2 — Early Churn Risk Analysis

- High-Risk Customers
- High-Risk Churn Rate
- Average Risk Score
- High-Risk Churned Customers
- Churn Rate by Risk Score
- Customer Distribution by Risk Level
- High-Risk Customers by Geography
- Customers by Age Group and Risk Level
- Credit Score vs Balance by Risk Level
- High-Risk Customer Details

---

## 💡 Business Insights

1. **High-risk customers** have a 56.11% observed churn rate.
2. Customers aged **50–60** show higher observed churn than customers under 30.
3. **Inactive customers** show higher churn than active customers.
4. Geography shows noticeable differences in customer churn.
5. Multiple customer attributes can be combined into a simple rule-based risk score for segmentation.

---

## 🔄 Project Workflow

```text
Raw Customer Data
        ↓
Python + Pandas
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Risk Score Creation
        ↓
Cleaned CSV
        ↓
Power BI
        ↓
DAX Measures
        ↓
Interactive Dashboard
        ↓
Business Insights
```

## 👤 Author

**Priyesh Singh**  
Aspiring Data Analyst | Python | SQL | Power BI
