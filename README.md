📉 Customer Churn Analysis

📌 Introduction

The Customer Churn Analysis project focuses on understanding the factors that drive customer attrition (churn) in a telecom company. By analyzing historical customer data, this project identifies patterns, risk factors, and actionable insights that help businesses improve customer retention strategies.

The analysis leverages Python, Jupyter Notebook, and data visualization to explore trends, correlations, and predictive indicators of churn. A detailed report (PDF) is also included for documentation of findings.

✨ Key Features

📊 Exploratory Data Analysis (EDA): Identifies important churn indicators such as tenure, contract type, internet services, and monthly charges.

🔍 Churn Insights: Helps understand which customer groups are most likely to churn.

📑 Comprehensive Report: Includes a PDF report summarizing analysis & findings.

🧮 Machine Learning Ready: Dataset prepared for potential churn prediction modeling.

📂 Project Structure
Customer-Churn-Data-Analysis/
│── Customer Churn.csv             # Raw dataset
│── TCA.ipynb                      # Jupyter Notebook (EDA & Analysis)
│── Telco Customer Churn Analysis.pdf  # Detailed report of findings
│── README.md                      # Project documentation

📊 Dataset Overview

Source: Telco Customer Churn dataset

Features include:

Customer demographics (gender, senior citizen, partner, dependents)

Account information (tenure, contract, payment method)

Services subscribed (phone, internet, streaming, etc.)

Financial details (monthly charges, total charges)

Target variable: Churn (Yes/No)

🔍 Key Insights

Customers with month-to-month contracts show higher churn rates compared to long-term contracts.

High monthly charges are strongly correlated with customer churn.

Customers using fiber optic internet tend to churn more compared to DSL users.

Long-tenure customers are less likely to churn, indicating loyalty over time.

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) → Data wrangling & visualization

Jupyter Notebook → Interactive analysis

PDF Report → Documented findings

🚀 How to Use

Clone the repository:

git clone https://github.com/subhaeng/Customer-Churn-Data-Analysis.git


Open the TCA.ipynb file in Jupyter Notebook / JupyterLab.

Run the notebook to explore churn analysis & visualizations.

Refer to the Telco Customer Churn Analysis.pdf for a summarized report.
