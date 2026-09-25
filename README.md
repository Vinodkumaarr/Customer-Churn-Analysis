# 📊 Customer Churn Analysis

A Python-based data analysis project that identifies the key drivers of customer churn and translates them into actionable retention strategies. The project covers the full analytics workflow — data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling — and culminates in an interactive dashboard that visualizes churn patterns across contracts, payment methods, services, and demographics.

---

## 📌 Overview

Customer churn — when a customer stops doing business with a company — directly impacts revenue and long-term growth. This project analyzes a customer dataset to answer three core questions:

- **Who is churning?** (demographics, tenure, contract type)
- **Why are they churning?** (pricing, service quality, payment friction)
- **What can be done about it?** (retention levers a business can act on)

Using **Pandas** and **NumPy** for data preprocessing and feature engineering, and machine learning for churn prediction, the project uncovers the strongest retention drivers and packages the findings into a business-ready dashboard.

---

## 🎯 Objectives

- Clean and prepare raw customer data for analysis
- Perform exploratory data analysis to uncover churn trends
- Engineer features that improve churn predictability
- Build and evaluate a machine learning model to classify at-risk customers
- Visualize churn KPIs and segments in an interactive dashboard
- Deliver clear, actionable recommendations to reduce churn

---

## 🖥️ Dashboard

The dashboard summarizes churn performance at a glance and lets stakeholders drill into the segments driving attrition.

![Churn Analysis Dashboard]<img width="1371" height="735" alt="Screenshot 2026-09-26 011648" src="https://github.com/user-attachments/assets/d2de1516-042a-4a6f-95b0-69f5233c56b8" />


**Key metrics tracked:**

| Metric | Value |
|---|---|
| Total Customers | 429 |
| Total Revenue | 21.00M |
| Retained Customers | 326 |
| Churn Rate | 24.01% |
| Churned Customers | 103 |
| Average Monthly Charges | 1.35K |
| Average Tenure | 35.75 months |

**Views included:**
- **Churn by Contract Type** — month-to-month vs. one-year vs. two-year contracts
- **Churn by Subscription Type** — Standard, Premium, Basic tiers
- **Total Revenue by State** — geographic revenue breakdown
- **Churn by Payment Method** — donut breakdown by payment channel
- **Churn by State** — geographic churn concentration (map view)
- **Monthly Charges vs. Churn** — pricing sensitivity scatter view
- **Churn by Internet Service** — churn split across service types
- **Churn by Senior Citizen** — churn behavior by age segment

> 📁 To reproduce this view, add your dashboard file (e.g. `dashboard.pbix`) to the repo and place a screenshot at `assets/churn-dashboard.png` so it renders here.

---

## 🧰 Tools & Technologies

| Category | Tools |
|---|---|
| Language | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Modeling | Scikit-learn |
| Dashboarding | Power BI |
| Environment | Jupyter Notebook / Anaconda |

---

## 🔍 Project Workflow

1. **Data Collection** — Import raw customer data (demographics, account info, service usage, billing, churn label).
2. **Data Cleaning** — Handle missing values, correct data types, remove duplicates/outliers.
3. **Exploratory Data Analysis (EDA)** — Analyze churn distribution across contract type, tenure, payment method, internet service, and monthly charges.
4. **Feature Engineering** — Encode categorical variables, create tenure buckets, derive revenue-related features.
5. **Modeling** — Train and evaluate classification models (e.g., Logistic Regression, Random Forest) to predict churn likelihood.
6. **Evaluation** — Assess model performance using accuracy, precision, recall, and ROC-AUC.
7. **Visualization** — Build an interactive dashboard summarizing churn KPIs and segment-level insights.

---

## 📈 Key Insights

- Churn is concentrated among **month-to-month contract customers**, while one-year and two-year contracts show significantly lower churn.
- **~24% overall churn rate**, with churned customers representing a meaningful share of lost recurring revenue.
- Certain **payment methods** and **internet service types** correlate with higher churn, pointing to friction points worth addressing.
- **Senior citizens** show a different churn pattern than the general customer base, suggesting a need for segment-specific retention offers.
- Customers with **shorter tenure** are disproportionately represented among churned accounts.

*(Update this section with the specific findings from your own EDA/model output.)*

---

## 💡 Business Recommendations

- Incentivize month-to-month customers to shift to longer-term contracts (e.g., discounts for annual plans).
- Investigate friction in higher-churn payment methods and simplify the billing experience.
- Launch targeted retention campaigns for high-risk segments identified by the model.
- Monitor tenure milestones (e.g., first 3–6 months) where churn risk is highest, and intervene proactively.

---

## 📂 Repository Structure

```
Customer-Churn-Analysis/
│
├── Data Analysis Project/     # Notebooks, scripts, and/or dashboard files
├── assets/                    # Images used in this README (e.g., dashboard screenshot)
├── anaconda_projects/db/      # Anaconda project metadata
└── README.md
```

> Update this tree to match your actual file and folder names once finalized.

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or Anaconda

### Installation

```bash
git clone https://github.com/Vinodkumaarr/Customer-Churn-Analysis.git
cd Customer-Churn-Analysis
pip install -r requirements.txt
```

### Usage

1. Open the analysis notebook inside `Data Analysis Project/` in Jupyter Notebook.
2. Run the cells sequentially to reproduce the data cleaning, EDA, and modeling steps.
3. Open the Power BI file (if included) to explore the interactive dashboard.

---

## 📬 Contact

**Vinod Kumar**
📧 vinodkumaarr22@gmail.com
🔗 [LinkedIn](https://linkedin.com/) · [GitHub](https://github.com/Vinodkumaarr) · [Portfolio](https://portfolio.com/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
