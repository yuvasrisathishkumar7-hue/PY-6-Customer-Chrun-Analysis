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
<li>Standard deviation</li>
<h5>Churn Analysis</h5>
<li>High churn customers</li>
<li>Low churn customers</li>
<li>Comparison between both groups</li>
<h5>Group-Based Analysis</h5>
<li>Age group vs churn</li>
<li>Gender vs churn</li>
<li>Active vs inactive customers</li>
<li>Number of products vs churn</li>
<h5>Relationship Analysis</h5>
<li>Balance vs churn</li>
<li>Credit score vs churn</li>
<li>Tenure vs churn</li>
 </ul> 
<hr>
 <h2>DATA VISUALIZATION</h2>

The project includes several visualizations:

<b> <i>

| CHART        | PURPOSE                       | GRAPH UNDERSTANDING / KEY POINTS                    |
| ------------ | ----------------------------- | --------------------------------------------------- |
| Bar Chart    | Churn distribution            | Shows number of churn vs non-churn customers        |
| Pie Chart    | Churn percentage              | Displays percentage of churned customers            |
| Histogram    | Age distribution              | Shows how customer ages are spread                  |
| Scatter Plot | Balance vs Credit Score       | Shows relationship between balance and credit score |
| Box Plot     | Balance vs churn              | Identifies variation and outliers                   |
| Heatmap      | Correlation between variables | Shows relationships between features                |

</b> </i>
<hr>

<h2>BAR CHART</h2>

<img width="476" height="363" alt="image" src="https://github.com/user-attachments/assets/1257d830-3e3e-45cc-a672-2645dd507011" />



<hr>

<h2>PIE CHART</h2>

<img width="358" height="327" alt="image" src="https://github.com/user-attachments/assets/3be55102-9d66-46f4-989a-29e6cf5cc145" />



<hr>

<h2>HISTOGRAM</h2>

<img width="449" height="348" alt="image" src="https://github.com/user-attachments/assets/322ddae4-e6a6-4c57-98f0-ba9388e10abb" />



<hr>

<h2>SCATTER PLOT</h2>

<img width="454" height="360" alt="image" src="https://github.com/user-attachments/assets/928b0d40-048e-4530-b213-92259633f71a" />



<hr>

<h2>BOX PLOT</h2>

<img width="476" height="364" alt="image" src="https://github.com/user-attachments/assets/15154387-8ce9-40e8-be89-f32b0354eadc" />



<hr>

<h2>HEATMAP</h2>

<img width="516" height="427" alt="image" src="https://github.com/user-attachments/assets/f39cc56e-559a-4282-8874-0fbd0fb3968d" />



<hr>

<h2>TECHNOLOGIES USED</h2>
<ul>
<li>Python</li>
<li>Pandas</li>
<li>NumPy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
</ul>
<hr>
<h2>EXPECTED OUTCOME</h2>
The analysis helps to:
<ul>
<li>Understand customer behavior</li>
<li>Identify high-risk churn customers</li>
<li>Detect patterns affecting churn</li>
<li>Support business decision-making</li>
<li>Improve customer retention strategies</li>
</ul>
<hr>
<h2>CONCLUSION</h2>
This project demonstrates how customer data can be analyzed using Python and data science techniques. By generating synthetic data and applying Exploratory Data Analysis (EDA), meaningful insights can be derived to understand customer behavior and reduce churn.
<hr>
