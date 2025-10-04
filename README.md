# Financial-risk-insights
Exploratory data analysis on 32K+ borrower records across the USA, UK, and Canada to evaluate credit risk patterns. The project identifies key factors influencing defaults, such as loan-to-income, 
debt-to-income, and credit utilization ratios.
## Problem Statement
Financial institutions face increasing challenges in assessing borrower risk due to varying income levels, credit histories, and loan behaviors.
This project aims to analyze borrower data across the USA, UK, and Canada to uncover patterns in default behavior, evaluate risk factors such as loan-to-income, debt-to-income,
and credit utilization ratios, and segment borrowers into risk categories. The goal is to provide actionable insights that can support smarter credit risk management and lending strategies.

## Process

### 1.Data Collection

Obtained the dataset from the ONYX Data Challenge.

Loaded borrower data consisting of loan details, income, demographics, and credit history.

### 2.Data Cleaning & Preprocessing

Removed anomalous records (e.g., unrealistic ages 123 & 144, invalid employment values).

Dropped irrelevant or inconsistent columns.

Standardized formats for income, loan amount, and categorical variables.

### 3.Exploratory Data Analysis (EDA)

Performed univariate and bivariate analysis to understand borrower profiles.

Drew Directed Acyclic Graphs (DAGs) to represent relationships between risk factors.

Computed key metrics: loan-to-income ratio, debt-to-income ratio, and credit utilization.

### 4.Visualization

Built interactive visualizations in Power BI to analyze:

Default probability by loan intent (Education, Medical, Personal, etc.).

Borrower segmentation by income, employment type, and demographics.

Risk patterns across USA, UK, and Canada.

Highlighted high-risk borrowers and compared risk categories across regions.

### 5.Insights & Reporting

Identified that UK borrowers have the highest default risk (due to higher credit utilization).

Found Canada to have more past delinquencies and higher debt-to-income ratios.

Delivered final insights through a PDF report summarizing borrower segmentation and default behaviors.
### Tools: 
Excel,Power BI

DAG

![image_alt](https://github.com/srividya1821/Financial-risk-insights-uncovering-borrower-default-trends-with-data-analytics/blob/166c46311ecd8fab63d0f5e0003ee3048b40e3da/Credit_Risk_DAG.png)



