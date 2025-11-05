# Credit Default Prediction

## Overview
This project predicts the probability that a customer will default on a loan or credit payment using machine learning.
The goal is to identify high-risk customers early to improve financial decision-making.

## Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn, SHAP
- Jupyter Notebook / Streamlit (optional app)

## Dataset
- Source: [Give Me Some Credit – Kaggle](https://www.kaggle.com/c/GiveMeSomeCredit)
- Rows: ~150,000
- Features include: age, income, debt ratio, credit utilization, delinquency history, etc.
- Target: `SeriousDlqin2yrs` (1 = default, 0 = no default)

## Project Steps
1. **Data Cleaning**
   - Handled missing values and outliers
   - Scaled numeric variables
2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix and class imbalance checks
   - Feature distributions and credit behavior trends
3. **Feature Engineering**
   - Created debt-to-income and late payment ratio features
4. **Modeling**
   - Logistic Regression, Random Forest, and XGBoost
   - Hyperparameter tuning using cross-validation
5. **Evaluation**
   - ROC-AUC, F1-score, precision-recall
   - SHAP summary for feature importance
6. **(Optional)** Deployed a Streamlit app to interactively test model predictions.

## Results
- Best model: **XGBoost**
- ROC-AUC: **0.87**
- Top predictors: Debt Ratio, Revolving Utilization, Delinquency Count

## Screenshots
*(Add plots here — confusion matrix, ROC curve, SHAP plot)*

## Future Work
- Incorporate credit bureau data
- Test deep learning (TabNet, AutoEncoders)
- Build API for integration with CRM systems

## Author
Katende Ukasha – Data Analyst
