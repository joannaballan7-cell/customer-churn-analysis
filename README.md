# Customer Churn Analysis

## Project Overview

This project analyzes customer churn data to identify patterns and factors that may influence customer retention. Using Python and data analysis techniques, I explored customer demographics, contract types, payment methods, and tenure to uncover insights that could help a business reduce customer loss.

The goal of this project was to answer business questions around why customers leave and identify opportunities for improving retention strategies.

## Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook
* GitHub

## Dataset

The analysis uses a telecommunications customer dataset containing customer account information, services, contract details, payment methods, and churn status.

## Business Questions Answered

* What percentage of customers are leaving the company?
* Which contract types have the highest churn rates?
* Does payment method impact customer churn?
* Are newer customers more likely to leave?

## Key Findings

### 1. Overall Customer Churn Rate

The overall churn rate was:

**26.54%**

Approximately one out of every four customers in the dataset left the company.

---

### 2. Contract Type and Churn

Month-to-month customers had the highest churn rate:

* Month-to-month: **42.71%**
* One-year contract: **11.27%**
* Two-year contract: **2.83%**

**Insight:** Longer-term contracts are associated with stronger customer retention.

---

### 3. Payment Method and Churn

Customers using electronic checks had the highest churn rate:

* Electronic check: **45.29%**

Automatic payment methods showed much lower churn rates.

**Insight:** Customers using electronic checks may require additional investigation into billing experience and customer engagement.

---

### 4. Customer Tenure and Churn

Churned customers had a much shorter average relationship with the company:

* Retained customers: **37.57 months average tenure**
* Churned customers: **17.98 months average tenure**

**Insight:** Early customer engagement and onboarding may be important opportunities for improving retention.

## Visualizations

### Churn by Contract Type

![Churn by Contract](charts/churn_by_contract.png)

### Churn by Payment Method

![Churn by Payment](charts/churn_by_payment.png)

### Tenure Distribution of Churned Customers

![Tenure Distribution](charts/tenure_distribution.png)

## Future Improvements

* Build a machine learning model to predict customer churn
* Create an interactive dashboard using Power BI
* Perform deeper customer segmentation analysis
* Analyze additional factors affecting retention
