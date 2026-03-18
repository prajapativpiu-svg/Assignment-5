# 💳 Credit Card Fraud Transaction Analysis – Data Analytics Report

## 📌 Project Overview
The **Credit Card Fraud Transaction Analysis Dashboard** is designed to monitor and analyze fraudulent credit card transactions using interactive visualizations. The dashboard helps identify fraud patterns, transaction trends, and high-risk transaction ranges.

The main goal of this project is to help financial institutions **detect suspicious transactions, monitor fraud rates, and gain insights into fraud behavior through data analytics.**

---

# 🎯 Objectives

The main objectives of this project are:

- Analyze **fraud transactions across different months**
- Identify **transaction amount ranges most affected by fraud**
- Understand the **distribution of fraud vs non-fraud transactions**
- Monitor **overall transaction activity**
- Provide **interactive filtering for deeper analysis**

---

# 🛠 Tools & Technologies

- **Microsoft Power BI** – Dashboard development and visualization  
- **Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – Calculations and measures  
- **Dataset** – Credit Card Transaction Dataset  

---

# 📊 Key Performance Indicators (KPIs)

| Metric | Value |
|------|------|
| Total Transactions | **100K** |
| Fraud Transactions | **1,000** |
| Average Transaction Amount | **2.50K** |
| Fraud Rate | **1%** |
| Maximum Transaction Amount | **5.00K** |

These KPIs provide a quick summary of the transaction dataset and fraud statistics.

---

# 📈 Dashboard Analysis & Insights

## 1️⃣ Fraud Transactions by Month

The **Fraud Transactions by Month** chart visualizes the monthly pattern of fraudulent activities.

### Key Observations

- Fraud cases fluctuate across months.
- A noticeable spike occurs in **August**.
- Fraud activity slightly decreases towards the end of the year.

**Insight:**  
Fraud activities may follow **seasonal patterns**, possibly influenced by increased transaction volumes or online shopping periods.

---

## 2️⃣ Transaction by Amount Range

This visualization groups transactions into different value ranges to analyze fraud concentration.

### Amount Categories

- **\< $1K**
- **$1K – $2.5K**
- **$2.5K – $5K**

### Key Observations

- The **$2.5K – $5K range records the highest fraud cases (511)**.
- Lower-value transactions have fewer fraud cases.

**Insight:**  
Fraudsters tend to target **medium to high transaction values** rather than very small amounts.

---

## 3️⃣ Fraud vs Non-Fraud Distribution

The **donut chart** shows the proportion of fraudulent and legitimate transactions.

| Type | Count |
|------|------|
| Non-Fraud Transactions | **99K (99%)** |
| Fraud Transactions | **1K (1%)** |

**Insight:**  
Fraud represents a small portion of total transactions but can still cause **significant financial risk**.

---

## 4️⃣ Total Transactions by Month

This chart displays the **overall monthly transaction volume**.

### Observations

- Transaction volume remains **relatively stable across months**.
- Minor variations appear throughout the year.

**Insight:**  
Consistent transaction volume indicates steady customer activity across the dataset period.

---

## 5️⃣ Fraud Transactions Table

The dashboard includes a **detailed table** showing top fraud transactions.

Displayed fields include:

- **Transaction ID**
- **Transaction Amount**
- **Fraud Indicator**

Conditional formatting is applied to visually highlight fraud indicators.

---

# 🎛 Dashboard Filters

The dashboard includes interactive slicers that allow users to explore data dynamically:

- **Transaction Date Filter** – Analyze transactions within a selected time range
- **Fraud Status Filter** – Filter fraud or non-fraud transactions
- **Amount Range Filter** – Focus on specific transaction value ranges

These filters allow users to perform **customized fraud analysis.**

---

# 📊 Key Findings

- Total transactions in the dataset reached **100,000**.
- **1,000 transactions were identified as fraudulent**, resulting in a **1% fraud rate**.
- The **$2.5K – $5K transaction range** shows the highest fraud activity.
- Fraud activity spikes around **August**, indicating possible seasonal behavior.
- The majority (**99%**) of transactions are legitimate.

---

# 🚀 Conclusion

The **Credit Card Fraud Transaction Analysis Dashboard** provides a clear and interactive way to analyze fraud patterns and transaction behavior.

By using data visualization and analytics tools like **Power BI**, organizations can:

- Monitor fraud trends
- Identify high-risk transaction ranges
- Detect unusual activity patterns
- Support data-driven fraud prevention strategies

This project demonstrates how **business intelligence dashboards can transform raw financial transaction data into meaningful insights for fraud monitoring and decision-making.**

---

## 📷 Dashboard Preview

![Fraud Dashboard](dashboard.png)