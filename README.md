Loan Approval Prediction Engine

A Data-Driven Approach to Automating Financial Decisions

⸻

Overview

This repository contains a machine learning project designed to predict loan approval outcomes. Built as part of my academic journey in Computer Science at VIT Bhopal, the project demonstrates practical applications of data cleaning, visualization, and predictive modeling to address a real-world financial challenge.

⸻

Problem Statement

In the financial sector, the loan approval process is often slow and subjective. This project automates the decision-making process by predicting loan approval outcomes using applicant attributes.

By integrating data-driven insights, the system helps:
	•	Minimize financial risks
	•	Reduce manual evaluation work
	•	Provide faster and more transparent responses to applicants

⸻

Workflow & Key Features

1. Data Cleaning & Preprocessing
	•	Handled missing values using methods like dropna
	•	Encoded categorical variables (e.g., Gender, Marital Status, Education) into numerical form

2. Exploratory Data Analysis (EDA)
	•	Visualized relationships between features and loan approval status
	•	Used Seaborn for detailed feature distributions and correlation insights

3. Model Training
	•	Implemented a Support Vector Machine (SVM) classifier with a linear kernel
	•	Tuned and trained on applicant data for binary classification

4. Model Evaluation
	•	Measured model performance using accuracy score
	•	Evaluated results on both training and unseen test data

5. Predictive System
	•	Developed a script to predict loan approval for single-instance inputs
	•	Demonstrates real-world applicability of the trained model

⸻

Dataset

The dataset consists of applicant information with the following features:
	•	Categorical: Gender, Married, Dependents, Education, Self_Employed, Property_Area
	•	Numerical: ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History
	•	Target Variable: Loan_Status (Y = Approved, N = Rejected)

⸻

Tech Stack
	•	Python – Primary programming language
	•	Pandas – Data manipulation and preprocessing
	•	NumPy – Numerical computations
	•	Scikit-learn – Data splitting, SVM model training, and evaluation
	•	Seaborn – Data visualization and EDA
	•	Jupyter Notebook – Interactive environment for analysis and documentation
