# Credit Risk Prediction Model

## Objective
Predict loan default probability to support credit decision-making and portfolio risk management.

## Business Problem
Financial institutions need to identify high-risk borrowers to minimize losses and optimize lending decisions. This model helps assess borrower risk proactively.

## Dataset
- Home Credit Default Risk or Lending Club Loan Data  
- Source: [Kaggle](https://www.kaggle.com)  
- Key Features: loan amount, income, credit utilization, payment history, employment length  

## Methodology
- **Data Preparation:** SQL extraction, data cleaning, feature engineering (income ratios, debt-to-income ratio, credit utilization)  
- **Modeling:** Logistic Regression, Random Forest, XGBoost  
- **Evaluation:** ROC-AUC, F1-score, precision, recall  
- **Optional A/B Testing:** Compare risk segmentation thresholds across customer cohorts  

## Pipeline / Architecture
SQL Database → Python Preprocessing → Model Training (Azure ML) → Predictions → Power BI / Tableau Dashboard


## Tech Stack
Python, SQL, Scikit-learn, XGBoost, Azure ML, Power BI, Tableau, Git/GitHub

## Deliverables
- Preprocessed dataset  
- Feature-engineered dataset  
- Trained ML models  
- Risk prediction dashboards  
- Azure ML retraining pipeline  

## Current Status
Phase 1 – Data Exploration & Feature Engineering (In Progress)

## Folder Structure
/data
/notebooks
/scripts
/models
/dashboard
/diagrams
README.md


## Next Steps
- Train and validate models  
- Develop interactive dashboards  
- Automate pipeline via Azure ML
