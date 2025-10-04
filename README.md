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
### Insights
📊 Project Insights – Credit Risk Analysis

Dataset Overview: Analyzed 32,574 borrowers across 3 countries, 9 states, and 18 cities.

 #### Borrower Profile:

Average income: $65.9K

Average loan amount: $9.6K

 #### Credit Ratios:

Loan-to-Income ratio: 0.17

Debt-to-Income ratio: 0.35

Credit Utilization ratio: 0.50

Average credit history length: 5.8 years

#### Default Risks:

Higher default probability among single borrowers.

Debt Consolidation and Education loans showed the highest default rates.

Borrowers with shorter credit history are more prone to default.

#### Country Comparison:

UK borrowers are riskiest with highest loan-to-income and credit utilization ratios.

Canada shows highest past delinquencies and debt-to-income ratio.

US borrowers show comparatively lower default risk.

#### Risk Segmentation:

555 high-risk acts vs. 153 low-risk acts.

Younger borrowers make up 94% of the dataset, with higher need for monitoring.

#### Loan Outcomes:

Default rate jumps from 14% (no past defaults) to 30.5% (with past defaults).

Strong link between poor credit history and higher probability of default.

#### Employment Factor:

Majority of borrowers are full-time employed (60%), but part-time and unemployed groups show higher risk tendencies.



