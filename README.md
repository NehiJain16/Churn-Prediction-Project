# Churn-Prediction-Project
Customer Churn Prediction &amp; Retention Strategy | Python, Power BI, ML

# Customer Churn Prediction and Power BI Dashboard

This project combines **machine learning** and **business intelligence** to identify customers at risk of churn, explain key factors influencing their behavior, and guide data-driven retention strategies through a **Power BI dashboard**.

---

## Project Overview

- **Goal**: Predict customer churn and visualize insights to support business decision-making.
- **Dataset**: [Telco Customer Churn Dataset - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Tools Used**:  
   Python (Pandas, Sklearn, XGBoost, Matplotlib, Seaborn)  
   Power BI (DAX, KPIs, Heatmaps, Drill-throughs)  
   Google Colab  

---

## ML Pipeline (Python)

- Data cleaning and preprocessing
- Label encoding and feature engineering
- Model training using:
  - Logistic Regression
  - Random Forest
  - XGBoost (Best Performance)
- Evaluation with **accuracy**, **confusion matrix**, **ROC-AUC**, and **feature importance**
- Final data exported to CSV for Power BI analysis

---

## Power BI Dashboard Highlights

- **Summary Page**:
  - KPIs: Total Customers, Churned Customers, Churn Rate, Monthly Revenue Loss
  - Churn Heatmap (e.g., by contract type, internet service)
  - Churn Probability Distribution
  - Slicers to filter by Churn Status, Contract, Internet Service

- **Top 10 High-Risk Customers Table**:
  - Sorted by churn probability
  - Includes Monthly Charges, Tenure, and service usage

- **Drill-through Customer Page**:
  - Shows selected customer's:
    - Demographics and usage
    - Recommended Action (via DAX logic)
    - Risk summary, churn note, and visual comparisons

- **Additional Features**:
  - Segment vs Individual Comparison with Conditional Formatting
  - Estimated Revenue Loss DAX
  - Notes Panel + Navigation buttons

---

## Key Insights

- Customers on **month-to-month contracts with fiber optic internet** are at highest risk
- Estimated **monthly revenue loss** due to churn is significant
- Churn likelihood increases with lower tenure and absence of add-on services
- Dashboard helps proactively identify and retain at-risk customers

---

## How to Use

1. Run the Python notebook (`.ipynb`) in Google Colab or Jupyter
2. Use the generated `churn_output_for_powerbi.csv` in Power BI
3. Open `churn_summary.pbix` in Power BI Desktop to explore visuals
4. Interact with drill-through pages, slicers, and KPIs for insights

---

## About Me

I'm a **Microsoft Certified: Power BI Data Analyst Associate** with hands-on experience in:
- Data modeling
- Dashboard design
- Python-based ML

> Let’s connect on [LinkedIn](https://www.linkedin.com/in/nehijain)!

---

## Feedback & Contributions

Feel free to raise an issue or fork this project to improve it further!


