🏦 Bank Customer Churn Prediction

This project aims to predict whether a customer will leave a bank (churn) based on their demographic and account activity information. By identifying potential churners, banks can take proactive steps to retain valuable customers and reduce loss.

📌 Problem Statement

Customer churn is a critical problem in the banking sector. Losing loyal customers affects revenue and growth. This project builds a predictive model using machine learning to identify customers likely to churn based on historical data.

 📌 Objectives
 
Understand factors that influence customer churn

Perform data cleaning and exploratory analysis

Build, evaluate, and compare classification models

Provide business recommendations based on insights

🗃️ Dataset Description
Each row represents a bank customer, with the following features:

CustomerId, Surname

CreditScore, Age, Gender

Tenure, Balance, NumOfProducts

HasCrCard, IsActiveMember

EstimatedSalary

Exited – Target variable (1 = churned, 0 = stayed)

🔍 Exploratory Data Analysis (EDA)
Visualized distributions and correlations of features

Analyzed churn rate across age, credit score, activity status, etc.

Identified key drivers for churn using graphs and plots

🤖 Model Building
Trained and evaluated multiple classification models:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Support Vector Machine (SVM)

📈 Model Evaluation
Used classification metrics:

Accuracy

Precision, Recall

F1-score

ROC-AUC Curve

Confusion Matrix


🔎 Key Insights
Higher churn among inactive members and older customers

Customers with low credit scores or high balance are more likely to leave

Activity status and number of products are strong indicators of loyalty

📊 Final Results
Best performing model: XGBoost (or replace with your best model)

Achieved high recall for churn class, useful for retention campaigns

🛠️ Tools & Technologies
Python

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn, XGBoost

Jupyter Notebook

📁 Project Structure

bank-churn-prediction/
│
├── data/                 # Dataset files
├── notebooks/            # EDA and model building notebooks
├── visuals/              # Graphs and charts
├── models/               # Trained model files
├── README.md             # Project overview
└── churn_prediction.ipynb # Main notebook

