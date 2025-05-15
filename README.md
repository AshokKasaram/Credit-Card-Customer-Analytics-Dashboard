# Credit-Card-Customer-Analytics-Dashboard

## Project Overview

This project builds an interactive Power BI dashboard to analyze bank customer churn and credit risk. Using data from 10K+ customer records, it visualizes churn patterns, high-risk segments, and customer demographics to help drive data-informed retention and risk mitigation strategies.

---

## Business Problem

Banks often struggle to proactively identify customers likely to churn or exhibit high credit risk. Without a data-driven approach, retention campaigns and risk mitigation are reactive and costly. The objective of this project is to:

- Analyze customer behavior and demographics.
- Identify churn drivers and high-risk customer profiles.
- Provide actionable insights through intuitive dashboards.

---

## Key Business Questions

- What percentage of customers are at risk of churning?
- Which customer segments (by age, gender, education, income) are most likely to churn?
- How does credit card utilization relate to customer risk levels?
- Which card categories have the highest credit limits and spending patterns?
- How can we empower business stakeholders to filter and explore customer risk in real-time?

---

## Methodology

### Data Preparation

- Cleaned and pre-processed a dataset of 10,127 bank customers.
- Removed unnecessary fields (e.g., Customer IDs).
- Created new calculated fields:
  - Churn indicator
  - Age Groups
  - Utilization Risk Band

### Dashboard Design

Created a multi-page interactive dashboard:

#### Page 1: Executive Overview
- KPIs for total customers, churn rate, average credit limit, and utilization.
- Churn breakdown by customer status.
- Customer distribution by age group.

#### Page 2: Demographics & Churn Patterns
- Churn rates by gender, education level, marital status, and income category.
- Age vs. utilization risk analysis.

#### Page 3: Segmentation & Risk Profiling
- Customer segmentation by utilization risk.
- Average credit limits and spending patterns by card category.
- Comparison of high-risk vs. low-medium risk customer counts.

---

## Key Findings

- **Overall churn rate:** 16.1%
- **High-risk customers (high utilization):** 39.6% of total customers
- **Younger and lower-income customers** showed a slightly higher tendency to churn.
- Certain card categories correlated with higher credit limits and spending.

---

## Conclusion

The dashboard empowers business leaders to:

- Understand customer risk profiles.
- Target high-risk groups with tailored retention campaigns.
- Improve resource allocation for customer service and risk management.

---

## Tools & Technologies

- Power BI Desktop
- DAX for advanced measures and calculated columns
- Microsoft Excel (Data preparation)

---

## Dataset

This project used a sample bank customer dataset for learning purposes.  
Data columns include demographics, customer behavior, and account activity.
