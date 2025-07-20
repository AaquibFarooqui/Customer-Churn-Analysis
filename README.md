# Customer Churn Analysis

Analyzed customer churn to identify exit trends, risk profiles, and behavioral insights using advanced data modeling and interactive dashboards.

This project simulates a real-world business case using structured bank customer data to explore the factors contributing to churn and provide stakeholders with clear, actionable insights through data storytelling.

---

##  Objectives

- Calculate and visualize the customer churn rate.
- Identify churn patterns across geography, gender, credit behavior, and active membership.
- Track monthly churn trends over time.
- Segment customers by key categories such as credit card ownership and membership status.
- Present insights through an interactive Power BI dashboard and supporting analysis.

---

##  Key Insights

- The overall **churn rate** is **20.37%** (2037 out of 10,000 customers).
- **France** shows the highest churn among all geographic locations.
- Most exit customers had **"Fair" or "Poor" credit ratings**.
- **Inactive members** are far more likely to churn than active ones.
- Slightly more **male customers** exited than females.
- Exit counts are higher in the **November–January period**, suggesting seasonal impact.

---

##  Notebook Highlights (`Bank_Customer_Churn_Analysis.ipynb`)

- Loaded data from `Bank_Churn.csv`, `CustomerInfo.csv`, and `dimensiontables.xlsx`.
- Checked for missing values (none found).
- Used Seaborn to visualize churn by:
  - Overall label (Exited vs. Retained)
  - Geography
  - Gender
- Calculated churn rate: **20.37%**
- Built a basic classification model (likely Logistic Regression):
  - **Accuracy:** 80.5%
  - **Precision (Churn Class):** 0.59
  - **Recall (Churn Class):** 0.14
  - The model performs better in predicting retained customers than exited ones.

---

##  Power BI Dashboard Overview

###  Page 1 – Customer Profile & Activity Overview  
- Total Customers: 10,000  
- Exit Customers: 2,037  
- Credit Card Holders: 7,055  
- Churn by Gender and Credit Category  
- Churn trends month-over-month  

---

###  Page 2 – Geographic Insights & Credit Type Comparison  
- Churn breakdown by country  
- Exit trends by year and credit score category  
- Churn vs. Credit Card Ownership by Credit Type  

---
