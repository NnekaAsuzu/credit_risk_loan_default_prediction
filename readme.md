# Credit Risk – Loan Default Prediction

**Author:** Nneka Asuzu  
**Domain:** Financial Services / Credit Risk Modeling  
**Tech Stack:** Python, SQL, Scikit-learn, XGBoost, SHAP, Power BI, Git/GitHub  
**Dataset:** Kaggle – Home Credit Default Risk or Lending Club Loan Data  
https://www.kaggle.com

---

## 1. Project Objective
Predict the likelihood of loan default to enable data-driven lending decisions and optimize portfolio risk management.

---

## 2. Business Problem
Financial institutions face losses when borrowers default on loans. Traditional credit scoring methods often fail to capture nonlinear patterns in borrower behavior.

This project explores:
- Predicting probability of loan default  
- Identifying key drivers of credit risk  
- Improving risk segmentation for lending decisions  

---

## 3. Dataset Overview
The dataset contains borrower-level financial and credit information, including:
- Loan characteristics (amount, purpose)  
- Income and employment details  
- Credit history and repayment behavior  
- Credit utilization and outstanding debt  

---

## 4. Project Status

This project is currently in development as an end-to-end credit risk modeling pipeline.

### Completed Work
- Data loading and initial exploration  
- Data cleaning (missing values, duplicates, outliers)  
- Feature engineering:
  - Debt-to-income ratio  
  - Credit utilization ratio  
  - Loan-to-income ratio  
- Baseline model (Logistic Regression)  
- Initial experiments with Random Forest and XGBoost  

### In Progress
- Hyperparameter tuning for tree-based models  
- Feature refinement and selection  
- Model evaluation improvements (ROC-AUC, F1-score optimization)  
- SHAP-based explainability analysis  
- Power BI dashboard development  

### Planned Work
- Azure ML deployment pipeline  
- Real-time scoring integration  
- Model monitoring and retraining pipeline  

---

## 5. Methodology

### Modeling Approach
- Logistic Regression (baseline)  
- Random Forest (non-linear benchmark)  
- XGBoost (final optimized model)  

### Evaluation Strategy
- ROC-AUC for ranking performance  
- Precision, recall, and F1-score for imbalance handling  
- Confusion matrix analysis  

### Explainability
- SHAP-based feature importance  
- Identification of key risk drivers  

---

## 6. Planned Enhancements
- Hyperparameter tuning using GridSearchCV or Optuna  
- Threshold optimization for risk-sensitive decisioning  
- Model pipeline structuring using Scikit-learn Pipelines  
- Power BI dashboard for risk segmentation (in progress)  
- Azure ML deployment simulation (future phase)  

---

## 7. Project Pipeline (Planned Architecture)

- Data Source (Kaggle Dataset or SQL)  
- Data Cleaning & Feature Engineering (Python)  
- Model Training (Logistic Regression, Random Forest, XGBoost)  
- Evaluation & Threshold Optimization  
- Explainability Layer (SHAP)  
- Dashboard (Power BI)  

---

## 8. Folder Structure
- `/data` → raw and processed datasets  
- `/notebooks` → EDA and modeling notebooks  
- `/scripts` → preprocessing and modeling scripts  
- `/models` → trained model files  
- `/dashboard` → Power BI dashboard files  
- `/diagrams` → architecture and workflow visuals  
- `README.md` → project documentation  

---

## 9. Key Skills Developed
- End-to-end machine learning pipeline design  
- Financial risk modeling and classification  
- Feature engineering for structured financial data  
- Handling class imbalance problems  
- Model evaluation using ROC-AUC and F1-score  
- Early-stage explainable AI (SHAP)  
- Data storytelling for financial decision support  

---

## 10. Next Steps
- Improve feature engineering and reduce multicollinearity  
- Tune XGBoost model for optimal performance  
- Implement SHAP explainability analysis  
- Build Power BI dashboard for risk segmentation  
- Package pipeline into reusable ML workflow  