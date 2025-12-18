# Loan-Approval-Prediction-ML
End-to-end Machine Learning project for Loan Approval Prediction using data preprocessing, SMOTE, feature scaling, and multiple classification models
📊 Loan Approval Prediction using Machine Learning
🔍 Project Overview

This project focuses on building an end-to-end Machine Learning classification system to predict whether a loan application will be Approved or Rejected based on applicant details and financial information.

The project covers the entire ML pipeline, including data preprocessing, exploratory data analysis (EDA), handling class imbalance, feature scaling, model training, evaluation, and prediction.

This project was completed as part of the AI Careers for Women (AICW) program, an impactful initiative by the Edunet Foundation, in collaboration with Microsoft and SAP, under the valuable mentorship of Abdul Aziz Md Sir.

🎯 Problem Statement

Financial institutions receive a large number of loan applications daily. Manually evaluating them is time-consuming and prone to bias.
This project aims to automate loan approval decisions using Machine Learning based on applicant attributes.

📁 Dataset Description

The dataset includes the following key features:

Loan ID

Number of Dependents

Education

Self Employed Status

Annual Income

Loan Amount

Loan Term

CIBIL Score

Residential, Commercial, Luxury & Bank Asset Values

Loan Status (Target Variable)

🛠️ Technologies & Tools Used

Python

Pandas & NumPy – Data handling

Matplotlib & Seaborn – Data visualization

Scikit-learn – Model building & evaluation

Imbalanced-learn (SMOTE) – Handling class imbalance

Pickle – Model serialization

⚙️ Project Workflow

Data Cleaning & Preprocessing

Removed inconsistencies in column names

Handled missing and infinite values

Applied log transformation to skewed features

Exploratory Data Analysis (EDA)

Distribution plots

Count plots for categorical features

Class imbalance analysis

Feature Engineering

Label Encoding for target variable

One-Hot Encoding for categorical features

Handling Class Imbalance

Applied SMOTE to balance Approved and Rejected classes

Feature Scaling

Used MinMaxScaler for normalization

Model Training

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Model Evaluation

Accuracy comparison

Confusion Matrix visualization

Prediction

User input-based loan approval prediction

📈 Model Performance

Models were evaluated using accuracy score

Random Forest Classifier achieved the best performance

Confusion matrices were used to analyze classification results

💾 Model Saving

The trained model and scaler were saved using pickle for future deployment:

model_RF.sav

scaler_model.sav
