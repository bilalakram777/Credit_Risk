 Credit Risk Analysis
Objective
Build a machine learning system that assesses customer creditworthiness and flags high-risk customers to help financial institutions reduce default rates.

 Dataset
Give Me Some Credit dataset, containing customer financial and demographic data.

Steps
Data Preprocessing

Handle missing values using imputation

Balance the dataset using SMOTE

Feature Engineering

Create features like income_to_debt and debt_to_income

Model Training

Train 3 classifiers:

Random Forest

Gradient Boosting

XGBoost

Evaluation

Evaluate using Classification Report, ROC-AUC, and Confusion Matrix

Risk Flagging

Customers are flagged as high-risk if their predicted probability of default > 0.5

Compare high-risk predictions across models

