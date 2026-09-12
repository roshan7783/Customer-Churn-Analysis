STRUCTURE 
OTT-Customer-Churn-Analysis/
├── churn_analysis_notebook.ipynb       # Python & SQL analysis code
├── customer_churn.db                  # Relational SQLite database
├── Churn_Analysis_Insights_Report.pdf # Executive PDF presentation
├── requirements.txt                   # Python package dependencies
└── README.md                          # Project documentation

# 📊 OTT Customer Churn & Revenue Loss Analytics

An end-to-end data analytics project examining customer churn patterns, subscription contract vulnerabilities, and lost Customer Lifetime Value (CLTV) for an Over-The-Top (OTT) streaming platform using **Python**, **SQL (SQLite)**, **Pandas**, and **Data Visualization**.

---

## Business Problem & Impact
Subscription churn directly degrades monthly recurring revenue (MRR). The goal of this analysis is to identify key churn drivers, quantify lost subscription revenue, and provide actionable business recommendations to boost customer retention.

### Key Executive Insights:
- **Overall Churn Rate:** **28.6%** (Retention Rate: 71.4%)
- **Contract Risk:** Monthly subscribers exhibit a **55.6% churn rate** compared to just **8.3%** for annual subscribers (6.7x higher churn risk).
- **Revenue Loss:** 74 churned subscribers accounted for an **~18% overall revenue drop**.
- **Cumulative Lost CLTV:** Estimated **$2,047** in lost customer lifetime value.
- **Geographic Anomaly:** Severe churn spike identified in **Karnataka** during September 2024.

---

## 🛠️ Tech Stack & Methodology
* **Programming:** Python 3.x
* **Database & SQL:** SQLite (`sqlite3`)
* **Data Wrangling:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## 💡 Strategic Recommendations
1. **Contract Migration:** Implement targeted discount strategies to incentivize monthly users to transition to annual plans.
2. **Basic Plan Overhaul:** Redesign features and content access for the Basic Plan to reduce high user drop-offs.
3. **Regional Intervention:** Investigate infrastructure and streaming quality issues in Karnataka to resolve localized churn spikes.

---
