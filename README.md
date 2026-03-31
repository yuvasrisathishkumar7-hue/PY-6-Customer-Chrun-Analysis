<h1 align="center"> CUSTOMER CHURN ANALYSIS SYSTEM (SYNTHETIC DATA) </h1>

<h2>PROJECT OVERVIEW</h2>

The Customer Churn Analysis System is a data analysis project that generates and analyzes synthetic customer data. The system creates a dataset of 100,000 customers with important features such as age, gender, account balance, credit score, tenure, and activity status.

The goal of this project is to perform Exploratory Data Analysis (EDA) to understand customer behavior, identify high-risk churn customers, and visualize relationships between different features.

Since real customer datasets are restricted due to privacy concerns, this project uses randomly generated synthetic data for analysis and learning purposes.
<hr>

<h2>PROBLEM STATEMENT</h2>

Businesses such as banks, telecom companies, and online services generate large amounts of customer data. However, analyzing this data manually is time-consuming and inefficient.

Additionally, real-world customer datasets are not easily available due to privacy and security restrictions. Therefore, this project generates synthetic data and performs analysis to identify churn patterns and risk factors.
<hr>

<h2>DATASET DESCRIPTION</h2>

The dataset contains 100,000 synthetic customer records with the following columns:
<b> <i>
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

</i> </b>
<hr>
<h2>PROJECT OBJECTIVES</h2>

The main objectives of this project are:
<ul>

<li>Generate a large synthetic customer dataset</li>
<li>Perform data cleaning and preprocessing</li>
<li>Check missing values and validate data</li>
<li>Perform statistical analysis (mean, median, mode, standard deviation)</li>
<li>Analyze customer behavior and churn patterns</li>
<li>Classify customers based on churn risk</li>
<li>Identify high-risk churn customers</li>
<li>Perform age-group and gender-based analysis</li>
<li>Study relationships between features</li>
<li>Visualize data using charts and graphs</li>
</ul>
<hr>

<h2>DATA CLEANING STEPS</h2>

The following data cleaning operations were performed:
<ul>
<li>Checked missing values using isnull()</li>
<li>Removed duplicate records</li>
<li>Converted categorical values into numerical format</li>
<li>Verified data types of each column</li>
<li>Ensured consistency in dataset</li>
</ul>
<hr>

<h2>CHURN CLASSIFICATION</h2>

Customers are classified based on the following condition:

<h5>HIGH CHURN CONDITION</h5>
<ul>
<li>Balance < 50,000</li>
<li>IsActiveMember = No</li>
<li>Tenure < 3</li>
  
<i> <b>
  
| CHURN VALUE | DESCRIPTION |
| ----------- | ----------- |
| 0           | No Churn    |
| 1           | High Churn  |

  
</b> </i>

<hr>

<h2>DATA ANALYSIS PERFORMED</h2>

The following analyses were conducted:

<ul>
  
<h5>Descriptive Statistics</h5>
<li>Mean</li>  
 <li>Median</li>  
 <li>Mode</li>
  
  Standard deviation
  
Churn Analysis

  High churn customers
  
  Low churn customers
  
  Comparison between both groups

Group-Based Analysis

  Age group vs churn

  Gender vs churn

  Active vs inactive customers

  Number of products vs churn

Relationship Analysis

  Balance vs churn

  Credit score vs churn

  Tenure vs churn

 </ul> 
