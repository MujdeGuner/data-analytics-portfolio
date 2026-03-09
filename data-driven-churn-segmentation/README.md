# Telco Customer Churn & Retention Strategy Analysis

## 📌 Project Overview
This project focuses on analyzing customer attrition (churn) within a telecommunications company. By examining customer demographics, service usage patterns, and contract details, the study identifies the primary drivers of churn and provides actionable insights to improve customer retention and stabilize Monthly Recurring Revenue (MRR).

## 🛠 Tech Stack & Methodology
* **Data Modeling:** Advanced Excel using Power Query for data transformation and cleaning.
* **Feature Engineering:** Developed custom segments based on tenure, contract type (Month-to-month, One year, Two year), and service usage.
* **Statistical Analysis:** * **Churn Rate Calculation:** Analyzed churn percentages across different customer cohorts.
    * **Revenue Impact Analysis:** Evaluated the relationship between Monthly Charges and attrition.
    * **Tenure Analysis:** Investigated the "critical period" where customers are most likely to leave.

## 📊 Key Insights & Findings

### 1. Contract & Service Influence
* **Contract Type:** Customers on **Month-to-Month** contracts exhibit a significantly higher churn rate compared to those on long-term (One/Two Year) commitments.
* **Service Adoption:** Users with "Fiber Optic" internet services show different churn characteristics compared to DSL, indicating a correlation between service type and loyalty.

### 2. Segment Performance (MRR & Tenure)
Based on the `MRR.csv` and `Chart.csv` analysis:
* Identified high-risk segments where **Average Monthly Charges** are high but **Tenure** is low. 
* Calculated the churn probability for specific personas (e.g., "Senior Citizens" vs. "Partners/Dependents").

### 3. Financial Impact
* Quantified the loss in **Monthly Recurring Revenue (MRR)** due to customer churn.
* Analyzed the "Total Charges" vs. "Tenure" to determine the Lifetime Value (LTV) of retained customers.

## 📂 Repository Structure
* `/Data`: Raw customer data and processed datasets.
* `/Analysis`: Pivot tables, MRR calculations, and churn metrics.
* `/Visuals`: Charts representing churn trends and segment distributions.

## 💡 Strategic Recommendations
* **Incentivize Long-term Contracts:** Offer targeted discounts to transition Month-to-Month customers to annual plans.
* **Proactive Support for High-Value At-Risk Customers:** Implement a retention program for segments with high Monthly Charges and declining engagement.
* **Service Quality Audit:** Investigate the high churn rate in specific internet service categories to ensure technical reliability.

---


