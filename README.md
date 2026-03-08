# Telco Customer Churn Analysis

![Dashboard](images/telco_dashboard.png)

## Overview

Customer churn analysis combining **Excel** and **Python machine learning** to predict at-risk customers and develop retention strategies for a telecommunications company.

**Results:** 79.8% ML accuracy | 287 high-risk customers identified | $280K revenue at risk | 163% projected ROI

---

## Business Problem

Telco loses **26.54% of customers annually** (1,869 customers, $1.45M revenue). This project identifies why customers leave and predicts who will leave next.

---

## Key Findings

**1. Contract Type Drives Churn**
- Month-to-month: 42.71% churn
- Two-year: 2.83% churn (15x better!)
- 88.55% of churned customers are month-to-month

**2. First Year is Critical**
- 47.68% churn in first 12 months
- Only 9.51% churn after 48+ months

**3. TechSupport Prevents Churn**
- Without TechSupport: 41.64% churn
- With TechSupport: 15.17% churn

**4. Fiber Optic Issues**
- Fiber Optic: 41.89% churn
- DSL: 18.96% churn
- 69% of churned customers use Fiber

---

## Machine Learning Results

![ML Results](images/ml_results.png)

**Model:** Random Forest Classifier

**Performance:**
- Accuracy: 79.8%
- ROC-AUC: 0.843
- Identifies 50.5% of churners before they leave
- Only 9.6% false alarms

**Top Predictors:**
1. Contract Type (22%)
2. Tenure (19%)
3. Total Charges (16%)
4. Monthly Charges (11%)

**High-Risk Customers:**

![High-Risk Customers](images/high_risk_top10.png)

- 287 customers identified (>70% churn probability)
- $280,000 annual revenue at risk
- Profile: 91% month-to-month, 84% no TechSupport, 73% Fiber Optic

---

## Recommendations

**Top 3 Actions:**

1. **Stop month-to-month contracts** for new customers → Save $456K annually
2. **Convert existing month-to-month** customers → Save $866K annually
3. **Bundle TechSupport** with all plans → Save $240K annually

**Expected Impact:**
- Reduce churn: 26.5% → 15%
- Save $1.46M annually
- 163% ROI over 3 years

---

## Tools Used

**Excel:**
- Data cleaning (7,043 customers, 26 features)
- PivotTables and analysis
- Interactive dashboard
- Business insights

**Python:**
- pandas, numpy, scikit-learn
- Random Forest machine learning
- matplotlib, seaborn visualizations

---

## Files

- `Telco_Churn_Analysis.xlsx` - Complete Excel analysis with dashboard
- `data/Telco-Customer-Churn.csv` - Original dataset
- `outputs/high_risk_customers.xlsx` - ML predictions (287 customers)
- `images/` - Dashboard and results screenshots

---

## How to Use

**Excel Analysis:**
1. Download `Telco_Churn_Analysis.xlsx`
2. Open in Excel
3. View sheets: RAW DATA, ANALYSIS, DASHBOARD, INSIGHTS, ML PREDICTIONS

**Python Model:**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
Run the analysis to recreate ML predictions.

---

## Data Source

**Dataset:** [Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
**Size:** 7,043 customers, 21 features  
**Target:** Churn (Yes/No)  
**Churn Rate:** 26.54%

---

## Skills Demonstrated

✅ Data Analysis  
✅ Machine Learning  
✅ Excel (PivotTables, Dashboards)  
✅ Python (pandas, scikit-learn)  
✅ Data Visualization  
✅ Business Strategy  
✅ ROI Analysis  



