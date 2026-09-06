# Telecom Customer Churn Analysis

Predictive analysis of customer churn for a telecom company, with actionable retention strategies derived from the findings.

## 📋 Overview

- **Objective:** Predict churn and derive actionable strategies to retain users in a competitive telecom environment
- **Dataset:** 5,000 customers, 14 features
- **Status:** ✅ Complete

## 📊 Key Results

| Metric | Value |
|---|---|
| Overall Churn Rate | 34.24% |
| Churned Customers | 1,712 |
| Retained Customers | 3,288 |
| Model Accuracy (ROC-AUC) | 75.82% |

### Top Findings
- **Contract type** is the #1 churn driver — month-to-month customers churn at 51.6%, vs. 19.5% for two-year contracts
- **New customers (0–6 months)** are a critical risk window, with 56.6% churn
- **Complaints** are strongly correlated with churn — 2+ complaints leads to 65% churn
- **Satisfaction score** below 5 corresponds to 70% churn, vs. 5% above a score of 8

### Risk Segmentation
| Segment | Count | Churn Rate | Recommended Action |
|---|---|---|---|
| Loyal | 307 | 11.7% | Retain & upsell |
| Low Risk | 337 | 31.2% | Monitor |
| Medium Risk | 316 | 54.7% | Targeted retention |
| High Risk | 40 | 70.0% | Immediate intervention |

## 🎯 Business Recommendations

1. **Contract Upgrade Program** — incentivize month-to-month customers to switch to long-term contracts
2. **Early Engagement Strategy** — structured onboarding and check-ins for customers in their first 6 months
3. **Complaint Resolution Excellence** — faster response times to reduce complaint-driven churn
4. **VIP Retention Program** — dedicated attention for the 40 identified high-risk customers

## 🛠️ Technical Stack

- **Data Processing:** Python (Pandas, NumPy), SQL
- **Machine Learning:** Scikit-learn (Logistic Regression, Random Forest)
- **Visualization:** Matplotlib, Seaborn

### Model Performance
| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression ⭐ | 72% | 0.7582 |
| Random Forest | 70% | 0.7471 |

## 📁 Repository Contents

- `CHURN_ANALYSIS_REPORT.md` / `.pdf` — Full analysis report: problem statement, methodology, findings, and recommendations
- `PROJECT_DELIVERABLES.md` / `.pdf` — Summary of project deliverables, results, and business impact
- `churn_analysis_dashboard.png` — 9-panel visual dashboard of churn drivers and segments



## 📖 How to Use This Repo

- **Quick review:** Start with `CHURN_ANALYSIS_REPORT.md` (~5 min read)
- **Full deliverables & business case:** See `PROJECT_DELIVERABLES.md`
- **Visual summary:** See `churn_analysis_dashboard.png`
