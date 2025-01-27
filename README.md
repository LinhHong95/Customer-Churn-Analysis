# Customer-Churn-Analysis
## Introduction
***What is churn?*** Customer churn refers to the percentage of customers who stop using a service over a specific period. Reducing churn improves customer retention, lowers acquisition costs, and directly enhances revenue, customer lifetime value, and profitability. 
This analysis is designed to provide senior managers with a clear, interactive dashboard that visualizes churned users, identifies churn reasons, and presents actionable solutions to reduce churn.

### Business Questions
- Create an overview dashboard for managers that displays the churn status of users and helps identify which users are part of the churn group.
- Develop solutions to improve the situation and reduce user churn.

### Target Stakeholders
- Sales Managers
- Customer Success Teams

### Key objectives
1. Develop a detailed churn profile.
2. Identify factors contributing to churn using exploratory data analysis (EDA).
3. Deliver actionable recommendations to reduce churn.

## Tools and Techniques
- **Tool**: Power BI for data analysis, data visualisation and storytelling.
- **Techniques**:
  + Exploratory Data Analysis (EDA) to uncover key trends.
  + Visual dashboards to present user-centric insights.

## Data Description
- Data dictionary
  
  <img width="768" alt="Image" src="https://github.com/user-attachments/assets/41ab55e5-c249-4257-91c3-93eee3a9ca08" />
  <img width="768" alt="Image" src="https://github.com/user-attachments/assets/e9e3ee4a-f24a-47bc-9cfd-eb59a140b157" />
  
- Source: https://assets.datacamp.com/production/repositories/5993/datasets/00187c4ac7192534646c5b71b260f0de880c6954/Case%20Study%20Analyzing%20Customer%20Churn%20in%20Power%20BI%20-%20Exercises%20and%20Datasets.pdf

## Workflow
### Step 1. Data Check
The dataset contains 6,687 rows and has undergone a quality check in Power Query to ensure accuracy, consistency, and completeness:
- Data Integrity
  - No duplicate rows detected.
  - All columns validated for relevance to analysis goals.
- Data Types: Each column has the correct data type
- Missing Values:
  - Missing values were identified in the Churn Category and Churn Reason columns.
  - These values were replaced with "Unknown" to maintain data consistency and enable downstream analysis.
### Step 2. Exploratory Data Analysis (EDA)
- Key Metric: Churn Rate = (Number of Churned Customers / Total Customers) × 100%
- Churn is analysed by various dimensions:
  - Demographics (e.g., age, location, gender)
  - Contract (e.g., Month-to-Month, One year, Two year)
  - Reason (e.g., Competitor, Attitude, Dissatisfaction, Price)
  - Services
- A further analysis of customer service is conducted to investigate how customer service impacts churn. 
### Step 3. Dashboard Development
### Step 4. Actionable Insights and Recommendations
<img width="1178" alt="Image" src="https://github.com/user-attachments/assets/8e2d0aca-17ec-4ba5-be18-e326f1f5c09b" />

## Summary
This project successfully delivered a comprehensive analysis of customer churn by identifying key factors such as age, contract type, and geographic trends. The retention strategies proposed—including enhancing customer support, aligning plans with usage, and promoting group memberships—are designed to reduce churn. This analysis equips senior managers, sales teams, and customer success team with the insights and solutions needed to improve customer retention and drive profitability.
