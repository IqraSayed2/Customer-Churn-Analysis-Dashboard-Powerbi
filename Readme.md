# Customer Churn Analysis and Retention Strategy

## Business Problem
Customer churn is a critical challenge for subscription-based businesses, as losing customers directly impacts revenue, profitability, and long-term growth.  
This project focuses on analyzing customer behavior to identify key churn drivers and propose actionable retention strategies to reduce customer attrition.

## Objective
- Analyze customer churn patterns using historical data  
- Identify high-risk customer segments  
- Design data-driven retention strategies  
- Build an interactive dashboard to support business decision-making  

## Dataset
- Telco Customer Churn dataset sourced from Kaggle  
- Contains customer demographics, service usage, contract details, charges, and churn status  
- Each record represents a unique customer  

## Tools & Technologies Used
- Power BI (data modeling, DAX, dashboard creation)
- DAX (measures and calculated columns)
- CSV dataset
- GitHub for project version control and documentation

## Key Analysis Performed
- Calculated overall churn rate and churned customer count  
- Analyzed churn by contract type, tenure, payment method, and monthly charges  
- Identified high-risk customer segments based on churn behavior  
- Built interactive visuals using slicers for dynamic exploration  

## Dashboard Overview
The Power BI dashboard includes:
- KPI summary (Total Customers, Churned Customers, Churn Rate)
- Churn analysis by contract type and customer tenure
- Impact of payment method and monthly charges on churn
- Interactive slicers for contract type, tenure group, and internet service

A snapshot of the final dashboard is available in the `screenshots/dashboard_overview.png` file.

## Key Insights
- Customers on month-to-month contracts exhibit significantly higher churn rates  
- New customers (0–12 months tenure) are the most vulnerable to churn  
- Customers using electronic check payment methods show the highest churn  
- Higher monthly charges are associated with increased churn risk  

## Retention Strategy
Based on the insights from the churn analysis, targeted retention strategies were developed focusing on:
- Encouraging long-term contracts
- Improving early-stage customer onboarding
- Promoting automatic payment methods
- Offering personalized pricing plans for high-value customers  

Detailed recommendations are documented in the `insights/retention_strategy.md` file.

## Repository Structure
customer-churn-analysis/
│
├── data/                  # Dataset used for analysis
├── dashboard/             # Power BI dashboard file
├── insights/              # Retention strategy document
├── screenshots/           # Dashboard screenshot
└── README.md              # Project documentation

## Conclusion
This project demonstrates how data analysis and visualization can be used to understand customer churn, identify key risk factors, and support strategic business decisions through actionable insights.
