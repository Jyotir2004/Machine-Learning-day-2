Loan Payment Exploratory Data Analysis (EDA)
This project focuses on the initial stages of data analysis and exploration using a customer loan payments dataset. The notebook demonstrates how to load raw data, perform structural inspections, and identify data quality issues such as missing values.

Project Overview
The primary objective is to gain a foundational understanding of the loan dataset’s structure and the distribution of key variables like loan status and borrower demographics.

Key Analytical Steps:
Data Loading: Importing and reading the Loan payments data.csv file using the Pandas library.

Structural Inspection: Utilizing .head() to preview the first few rows of the dataset, including features like Loan_ID, Principal, terms, and loan_status.

Missing Value Analysis: Quantifying null values across the dataset using .isnull().sum(). This reveals significant missing data in columns such as paid_off_time (100 missing) and past_due_days (300 missing).

Statistical Visualization: Leveraging Seaborn and Matplotlib to generate exploratory plots (e.g., age distribution or loan status counts) to identify trends within the lending data.

Technologies Used
Python 3

Pandas & NumPy: For data manipulation and numerical operations.

Seaborn & Matplotlib: For statistical data visualization.

Dataset Summary
The dataset contains 500 records with 11 core features:

Financials: Principal, terms, past_due_days.

Timestamps: effective_date, due_date, paid_off_time.

Demographics: age, education, Gender.

Targets: loan_status (e.g., PAIDOFF, COLLECTION).
