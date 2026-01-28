# Customer_Churn_Prediction

## 📊 Project Overview
This project focuses on analyzing customer behavior and building a machine learning model to predict customer churn using the Telco Customer Churn dataset. The objective is to help businesses identify customers at risk of leaving and enable data-driven retention strategies.

---

## 🎯 Objective
- Build an end-to-end data science pipeline for customer churn prediction  
- Identify key factors influencing customer churn  
- Compare multiple classification models to select the best-performing model  

---

## 📁 Dataset
- *Source:* Telco Customer Churn Dataset  
- *Records:* ~7,000 customers  
- *Target Variable:* Churn (Yes / No)  
- *Features:* Demographics, services, billing, and contract information  

---

## 🔍 Project Workflow

### 1. Data Collection & Cleaning
- Loaded dataset using Pandas  
- Converted TotalCharges to numeric and handled missing values  
- Transformed target variable into binary format (0/1)  

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution and class imbalance  
- Visualized churn behavior using:
  - KDE plots
  - Count plots
  - Correlation heatmaps  
- Identified churn drivers such as contract type and monthly charges  

### 3. Data Preprocessing
- Dropped irrelevant columns (Customer ID)  
- Applied one-hot encoding to categorical variables  
- Scaled numerical features using StandardScaler  
- Used stratified train-test split  

### 4. Model Building & Evaluation
- Trained classification models:
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Random Forest  
- Evaluated models using:
  - Accuracy
  - Confusion Matrix
  - Classification Report  

### 5. Results & Insights
- Compared model performances to identify the best model  
- Extracted business insights to support customer retention strategies  

---

## 🧰 Tools & Technologies
- *Programming Language:* Python  
- *Libraries:* Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- *Techniques:* EDA, Feature Engineering, Classification Modeling
