📊 Telco Customer Churn – Data Analysis & Visualization
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) and Data Visualization on the Telco Customer Churn Dataset.

The main objective is to analyze customer behavior and identify patterns that influence customer churn.

This project demonstrates practical usage of:

Python

Pandas

NumPy

Matplotlib

Seaborn

📂 Dataset Information

The dataset used in this project:

Name: WA_Fn-UseC_-Telco-Customer-Churn.csv

Description: Contains customer demographic information, account details, services subscribed, and churn status.

Target Variable: Churn

Key Features:

tenure

MonthlyCharges

TotalCharges

Contract

InternetService

PaymentMethod

Churn

🎯 Project Objectives

Perform data cleaning and preprocessing

Identify missing values and handle them

Perform statistical analysis

Visualize relationships between variables

Understand factors influencing customer churn

🛠️ Technologies Used

Python 3.x

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib – Basic visualization

Seaborn – Advanced visualization

📊 Steps Performed
1️⃣ Data Loading

Loaded dataset using Pandas

Displayed shape and preview of data

2️⃣ Data Inspection

Checked data types

Identified missing values

Generated statistical summary

3️⃣ Data Cleaning

Converted TotalCharges to numeric

Handled missing values using median imputation

4️⃣ Exploratory Data Analysis (EDA)

Performed:

Correlation analysis

Groupby analysis

Aggregation statistics

5️⃣ Data Visualization

Created:

Count Plot (Churn distribution)

Histogram (Monthly Charges distribution)

Box Plot (Charges vs Churn)

Bar Plot (Contract vs Charges)

Heatmap (Correlation matrix)

Pairplot (Feature relationships)

📈 Key Insights

Customers with Month-to-Month contracts show higher churn.

Higher Monthly Charges are associated with increased churn.

Longer tenure customers are less likely to churn.

Contract type strongly impacts customer retention.