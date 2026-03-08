# Telco Customer Churn Analysis

![Dashboard](images/telco_dashboard.png)

## 📊 Project Overview

Analysis of 7,043 telecom customers to predict churn and identify retention opportunities using **Excel** and **Python Machine Learning**.

**Key Results:**
- 🎯 79.8% ML prediction accuracy
- 💰 $280K revenue at risk identified
- 👥 287 high-risk customers flagged
- 📈 163% projected ROI

---

## 🎯 Problem

Telco faces **26.54% churn rate** (1,869 customers, $1.45M lost revenue annually). Need to identify why customers leave and who will leave next.

---

## 📈 Key Findings

### 1. Contract Type Drives Churn
- Month-to-month: **42.71% churn**
- Two-year: **2.83% churn** (15x difference!)
- 88.55% of churned customers are month-to-month

### 2. First Year is Critical
- **47.68% churn** in first 12 months
- Only **9.51% churn** after 48+ months
- Early customer experience is broken

### 3. TechSupport Prevents Churn
- Without TechSupport: **41.64% churn**
- With TechSupport: **15.17% churn**
- 26.5 percentage point impact

### 4. Fiber Optic Has Issues
- Fiber Optic: **41.89% churn**
- DSL: **18.96% churn**
- 69% of churned customers use Fiber

---

## 🤖 Machine Learning Results

![ML Results](images/ml_results.png)

**Model:** Random Forest Classifier

**Performance:**
- Accuracy: **79.8%**
- ROC-AUC: **0.843** (Excellent)
- Identifies **50.5%** of churners before they leave
- Only **9.6%** false alarms

**Top Predictors:**
1. Contract Type (22% importance)
2. Tenure (19%)
3. Total Charges (16%)
4. Monthly Charges (11%)

**High-Risk Customers:**

![High-Risk Customers](images/high_risk_customers_top10.png)

- **287 customers** identified with >70% churn risk
- **$280,000** annual revenue at risk
- **91%** on month-to-month contracts
- **84%** without TechSupport

---

## 💡 Recommendations

**Critical Actions:**
1. **Stop offering month-to-month** to new customers → Save $456K
2. **Convert existing month-to-month** customers → Save $866K
3. **Bundle TechSupport** with all plans → Save $240K
4. **Fix Fiber Optic** service quality → Save $352K

**Expected Impact:**
- Reduce churn from **26.5% → 15%**
- Save **$1.46M annually**
- **163% ROI** over 3 years

---

## 🛠️ Tools Used

**Excel:**
- Data cleaning (7,043 rows, 26 columns)
- PivotTables for analysis
- Interactive dashboard
- Business insights

**Python:**
- pandas, numpy (data processing)
- scikit-learn (Random Forest ML)
- matplotlib, seaborn (visualizations)

---

## 📁 Files

- `Telco_Churn_Analysis.xlsx` - Complete Excel analysis with dashboard
- `Churn_Prediction_Model.ipynb` - Python ML model
- `data/` - Original dataset
- `outputs/high_risk_customers.xlsx` - 287 predicted churners
- `images/` - Visualizations

---

## 📊 Skills Demonstrated

✅ Data cleaning & analysis  
✅ Statistical analysis  
✅ Machine learning (classification)  
✅ Feature engineering  
✅ Data visualization  
✅ Dashboard design  
✅ Business recommendations  
✅ ROI calculation  

**Tools:** Excel (Advanced), Python, pandas, scikit-learn, Jupyter

---

## 📚 Data Source

**Dataset:** [Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
**Size:** 7,043 customers, 21 features  
**Target:** Churn (Yes/No)

