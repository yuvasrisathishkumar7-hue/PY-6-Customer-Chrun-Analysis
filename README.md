CUSTOMER CHURN ANALYSIS SYSTEM (SYNTHETIC DATA)

PROJECT OVERVIEW

The Customer Churn Analysis System is a data analysis project that generates and analyzes synthetic customer data. The system creates a dataset of 100,000 customers with important features such as age, gender, account balance, credit score, tenure, and activity status.

The goal of this project is to perform Exploratory Data Analysis (EDA) to understand customer behavior, identify high-risk churn customers, and visualize relationships between different features.

Since real customer datasets are restricted due to privacy concerns, this project uses randomly generated synthetic data for analysis and learning purposes.

PROBLEM STATEMENT

Businesses such as banks, telecom companies, and online services generate large amounts of customer data. However, analyzing this data manually is time-consuming and inefficient.

Additionally, real-world customer datasets are not easily available due to privacy and security restrictions. Therefore, this project generates synthetic data and performs analysis to identify churn patterns and risk factors.

DATASET DESCRIPTION

The dataset contains 100,000 synthetic customer records with the following columns:

| COLUMN          | DESCRIPTION                    |
| --------------- | ------------------------------ |
| Customer_ID     | Unique customer ID             |
| Age             | Customer age (18–70 years)     |
| Gender          | Male / Female                  |
| Tenure          | Years with company (0–10)      |
| Balance         | Account balance (0–200,000)    |
| CreditScore     | Credit score (300–900)         |
| EstimatedSalary | Annual income (10,000–150,000) |
| NumOfProducts   | Number of products used (1–4)  |
| IsActiveMember  | Yes / No                       |
| Churn           | 0 = No, 1 = Yes                |

PROJECT OBJECTIVES

The main objectives of this project are:

Generate a large synthetic customer dataset

Perform data cleaning and preprocessing

Check missing values and validate data

Perform statistical analysis (mean, median, mode, standard deviation)

Analyze customer behavior and churn patterns

Classify customers based on churn risk

Identify high-risk churn customers

Perform age-group and gender-based analysis

Study relationships between features

Visualize data using charts and graphs

DATA CLEANING STEPS

The following data cleaning operations were performed:

Checked missing values using isnull()

Removed duplicate records

Converted categorical values into numerical format

Verified data types of each column

Ensured consistency in dataset

CHURN CLASSIFICATION

Customers are classified based on the following condition:

HIGH CHURN CONDITION

Balance < 50,000

IsActiveMember = No

Tenure < 3

| CHURN VALUE | DESCRIPTION |
| ----------- | ----------- |
| 0           | No Churn    |
| 1           | High Churn  |

DATA ANALYSIS PERFORMED

The following analyses were conducted:

✔ Descriptive Statistics
Mean
Median
Mode
Standard deviation
✔ Churn Analysis
High churn customers
Low churn customers
Comparison between both groups
✔ Group-Based Analysis
Age group vs churn
Gender vs churn
Active vs inactive customers
Number of products vs churn
✔ Relationship Analysis
Balance vs churn
Credit score vs churn
Tenure vs churn
