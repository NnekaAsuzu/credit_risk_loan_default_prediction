# Credit Risk Prediction Model

**Author:** Nneka Asuzu  
**Tools Used:** Python, SQL, Scikit-learn, XGBoost, Azure ML, Power BI, Tableau, Git/GitHub  
**Dataset:** Home Credit Default Risk or Lending Club Loan Data ([Kaggle](https://www.kaggle.com))

---

## 1. Project Objective
Predict the likelihood of loan default to enable data-driven lending decisions and optimize portfolio risk management.

---

## 2. Business Problem
Lending institutions face losses due to borrowers defaulting. Early identification of high-risk clients is critical to:

- Minimize financial losses  
- Improve credit decision-making  
- Optimize portfolio risk segmentation  

Key questions:

1. Which borrowers have the highest risk of default?  
2. What features (income, debt, credit utilization) are predictive of defaults?  
3. How can risk segmentation be applied to guide lending policies?  

---

## 3. Dataset Overview
- **Source:** Kaggle – Home Credit Default Risk or Lending Club  
- **Core Features:** loan amount, income, credit utilization, payment history, employment length  
- **Optional SQL Integration:** Extract data from internal financial databases  

**Cleaning & Feature Engineering:**
- Standardize columns and data types  
- Handle missing values and outliers  
- Encode categorical variables  
- Generate derived features:  
  - `debt_to_income = debt / income`  
  - `credit_utilization = balance / credit_limit`  
  - `loan_income_ratio = loan_amount / income`  

---

## 4. Methodology

**Phase 1 – Data Preparation**
- SQL extraction → Python preprocessing → feature engineering  

**Phase 2 – Modeling**
- Logistic Regression (baseline)  
- Random Forest (nonlinear patterns)  
- XGBoost (high performance)  
- Hyperparameter tuning via GridSearchCV  

**Phase 3 – Evaluation**
- Metrics: ROC-AUC, F1-score, precision, recall  
- Confusion matrix visualization  
- Feature importance analysis  

**Phase 4 – Optional A/B Testing**
- Compare risk segmentation thresholds across borrower cohorts  
- Statistical evaluation of thresholds and strategies  

---

## 5. Pipeline / Architecture

SQL Database → Python Preprocessing → Model Training (Azure ML) → Predictions → Power BI / Tableau Dashboard


---

## 6. Tech Stack
Python, SQL, Scikit-learn, XGBoost, Azure ML, Power BI, Tableau, Git/GitHub

---

## 7. Deliverables
- Preprocessed and feature-engineered datasets  
- Trained ML models (Logistic Regression, Random Forest, XGBoost)  
- Risk prediction dashboards  
- Azure ML retraining and scoring pipeline  

---

## 8. Current Status
**Phase 1:** Data Exploration & Feature Engineering (In Progress)  

---

## 9. Folder Structure 📁
- `/data` → raw and processed datasets  
- `/notebooks` → EDA and modeling notebooks  
- `/scripts` → preprocessing and modeling scripts  
- `/models` → trained model files  
- `/dashboard` → Power BI/Tableau dashboard files  
- `/diagrams` → architecture, workflow diagrams  
- `README.md` → project documentation  

---

## 10. Next Steps
1. Train and validate models  
2. Develop interactive dashboards for risk visualization  
3. Automate scoring and retraining pipelines via Azure ML  
4. Integrate SQL pipelines for real-time data extraction


