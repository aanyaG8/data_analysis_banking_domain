# **🏦 Banking Risk Analysis Dashboard**

This repository showcases a Banking Risk Analysis project where I utilized Power BI, SQL, and Python (Jupyter Notebook) to perform a complete end-to-end analysis on customer banking data to identify and visualize potential financial risks.

## 📊 Power BI Dashboard Report

View the full dashboard PDF here:

👉 [Power BI Dashboard Pages PDF](./data_analysis_banking_domain/PowerBl_dashboard_pages.pdf)


------

# **🎯 Project Objective**

To analyze customer financial behavior and identify risk-prone customers based on loans, deposits, income, credit history, and demographic features. The project helps financial institutions make data-driven decisions to reduce default risk and improve lending policies.

------

## **🛠️ Tools & Technologies Used**

Power BI – Dashboard creation, DAX measures, and KPIs

SQL – Data querying and transformation

Python (Jupyter Notebook) – Exploratory Data Analysis (EDA) using Pandas, Matplotlib, and Seaborn

Python-SQL Connector – Integrated dataset directly from database to Jupyter Notebook

------

## **🧩 Project Workflow**

### **1. Data Loading & Cleaning**
   
Imported dataset into Power BI and Jupyter

Used SQL queries for filtering, conditional formatting and performing aggregation.

Handled missing values and normalized data types in Python

### **2. Exploratory Data Analysis (EDA)**
Conducted in Jupyter Notebook:

#### 🧹 Data Cleaning:

Checks for null values

Drops unnecessary or duplicate rows/columns

Converts data types (e.g., date parsing)

Visualizes distributions (histograms, boxplots)

Analyzes customer demographics (e.g., age, gender)

Correlation analysis on numerical features

##### 📌 Key Insights:

Identifies trends or outliers in customer attributes

Highlights potential data quality issues

##### 📝 Output:

Cleaned dataset ready for further analysis or modeling


### **3. Power BI Dashboards**
   
Created four interactive dashboards:

#### 🔹 Home Page
Total Deposits, Loans, Customers

KPI Cards with slicers for Gender, Age

#### 🔹 Loan Analysis
Loan amount by Age group, Income band, Credit Card Count

Loan risk weighting distribution

##### 🔹 Deposit Analysis
Total and segmented deposits (Checking, Saving, Foreign)

Visualization by gender, properties owned

#### 🔹 Risk Analysis Dashboard

Risk Categorization (High, Medium, Low)

Cross-analysis of risk vs age, properties, and loan balance

Used calculated columns to flag risk levels

### **4. 📊 Key KPIs Visualized**

Loan-to-Deposit Ratio

Avg Loan lent

Avg loan borrowed by clients using Occupation
