# BANK-CUSTOMER-CHURN-ANALYSIS

## Table Of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Summary](#summary)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
- [References](#references)
  
### Project Overview
---

The goal of this project is to understand why some customers leave the bank (churn) and to predict which customers are likely to leave. This will help the bank improve customer retention by identifying at-risk customers and offering strategies to keep them.

![Screenshot (258)](https://github.com/user-attachments/assets/511966ad-9cff-46d5-9992-0a4788608949)

![Screenshot (259)](https://github.com/user-attachments/assets/62e452cc-42d0-43d3-96c7-95a73d140b02)

### Data Sources
---

Bank Customer Churn: The Primary Dataset used for this analysis is the "Bank_Churn.csv" file, This data source collectively provide insights into customer demographics, financial status, behavior, and churn outcomes.

### Tools
---
- Excel - Data Cleaning [Download Here](https://app.mavenanalytics.io/datasets?search=Bank)
- Power BI - Data Analysis / Creating Dashboards

### Data Cleaning
---
In the initial Data preparation Phase, We performed the Following Tasks:
1. Data Loading and Inseption
2. Removing Duplicates
3. Cleaning and Formatting 
   
Removing Duplicates:
We Checked for duplicate rows based on CustomerId to ensure each record is unique.
Remove duplicates to avoid skewing the analysis.

Data Formatting:
We Verified and corrected data types (e.g., ensure CreditScore, Balance, and EstimatedSalary are numeric, while under Geography we corrected some Countries wrongly spelt).
We Converted binary fields like HasCrCard, IsActiveMember, and Exited that has integers (0 and 1) to (Yes and No).

### Explanatory Data Analysis
---
Recommended Analysis
- What attributes are more common among churners than non-churners? Can churn be predicted using the variables in the data?
- What do the overall demographics of the bank's customers look like?
- Is there a difference between German, French, and Spanish customers in terms of account behavior?
- What types of segments exist within the bank's customers?

### Data Analysis 
---
 These analysis steps, We uncover patterns in customer behavior, segment customers based on their likelihood to churn, and generate actionable insights that the bank can use to enhance customer retention efforts.

### Results
---

1. Churn Rate: Approximately 20% of the bank's customers have left, highlighting an opportunity for improvement in customer retention.

2. Key Drivers of Churn:

- Low Balances: Customers with low or zero balances are more likely to churn.
- Geography: German customers churn at a higher rate than those from France or Spain.
- Age: Younger customers (20s-30s) are more likely to leave, while older customers are more loyal.
- Product Usage: Customers with only one product tend to churn more; multiple product users are more likely to stay.
- Active Membership: Inactive customers are at higher risk of churning.

3. Customer Segmentation Insights:

- High-Value Customers: Customers with high balances and multiple products are valuable and less likely to churn.
- High-Risk Segments: Younger, low-balance, single-product users are at high risk of leaving.

### Summary
---
The bank customer churn dataset contains information on 10,000 customers, tracking if they’ve stayed or exited the bank. Key features include:

- Demographics: Country, gender, age.
- Financials: Credit score, balance, estimated salary.
- Account Behavior: Number of products, credit card ownership, active status, tenure.
- Churn Outcome: Indicates if a customer has churned (1) or stayed (0)

### Recommendation
---
Based on the analysis We recommend the following actions:
-  Run campaigns targeting inactive customers with incentives (e.g., rewards for account activity) to encourage them to become active users.
-  Encourage single-product users to explore additional bank services, such as savings accounts, loans, or credit cards, which are linked to higher retention.
-  Since German customers show higher churn, consider conducting customer satisfaction surveys to identify specific needs or pain points and improve services accordingly.
-  Younger customers are more likely to churn; introducing mobile-friendly, flexible banking options can improve their engagement.
-  For customers with high balances or multiple products, implement loyalty or rewards programs to recognize and retain these valuable customers.

### Limitations 
---
- Only includes customers from France, Germany, and Spain, which limits the generalizability of insights to other regions.
- Financial information like balance and estimated salary may have outliers or inaccuracies that could skew analysis if not carefully managed.
- The dataset lacks detailed behavioral metrics, such as transaction frequency or service usage, which could provide a more significance view of customer engagement.

### References
---
[Download here Kaggle](https://www.kaggle.com/datasets/akanshachomal/bank-churn-customer-analysis)

😃

💻

🏦
|Heading1|Heading2|
|--------|--------|
|Microsoft Excel|PowerBI|
