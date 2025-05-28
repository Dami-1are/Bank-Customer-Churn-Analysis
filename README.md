# Bank-Customer-Churn-Analysis
This analysis investigates customer behavior and identifies key drivers of churn, using real-world banking data.

## Table of Content

- [Project Overview](project-overview)
- [Objectives](objectives)
- [Tools](tools)
- [Descriptive-Data-Analysis](descriptive-data-analysis)
- [Results/Findings](results/findings)
- [Conclusion](Conclusion)
- [Recommendation](recommendation)

### Project Overview
---

Customer churn poses a significant challenge in the banking sector, affecting long-term profitability and customer lifetime value. This analysis investigates customer behavior and identifies key drivers of churn, using real-world banking data. The insights derived are aimed at supporting customer retention strategies and improving overall service delivery.


### Objectives

- Identify Churn Drivers (Understand the demographic and behavioral factors contributing to customer churn).

- Assess Customer Profiles (Segment customers based on age, balance, tenure, geography, and other features).

- Evaluate Bank Performance Metrics (Examine KPIs such as churn rate, average balance, and product usage).

- Regional & Gender Influence (Determine how geography and gender influence customer retention).

- Develop Data-Driven Retention Strategies (Recommend actions to reduce churn based on predictive patterns).

### Data Cleaning

The dataset contains:
- Categorical Data: Geography, Gender, HasCrCard, IsActiveMember, Exited.

- Numerical Data: Age, Balance, Tenure, EstimatedSalary, CreditScore, NumOfProducts

### Steps Taken:

- Removed null or duplicate entries (none found in Power BI model).

- Verified data types (e.g., Exited as binary, Balance as float).

- Filtered out outliers where necessary (e.g., zero balance with high tenure).

- Standardized column labels and values for visual clarity

### Tools

-  Power BI – Used for modeling, dashboarding, and visualization.

-  Microsoft Excel – Used for exploratory cleaning and pre-modeling steps.


### Results/Findings

1. Overall Churn Rate

    Churned Customers: 2,037

    Churn Rate: 20.4% (relatively high)


2. Age & Churn Relationship

    Customers aged 40+ had significantly higher churn rates.

    Churn likelihood increases with age, peaking around 45–50 years.


3. Balance and Churn

    Customers with a high balance (> $100,000) are more likely to churn.

    This suggests that high-value clients may feel underserved or better targeted by competitors.

4. Tenure vs. Churn

    No direct correlation found between tenure and churn.

    Long-standing customers churn at almost the same rate as newer ones.

5. Geography

    Region	Churn Rate

    Germany	32%
    France	16%
    Spain	15%

    Customers in Germany are nearly twice as likely to churn compared to other regions.

6. Gender

    Female customers have a higher churn rate (~25%) than males (~16%).

7. Customer Activity

    Inactive customers churned at a rate of 27%, while active ones were at 14%.

    Activity level is a strong retention indicator.

8. Products Owned

    Customers with 1 product had the highest churn rate (25%).

    Those with 2 or more products showed lower churn, indicating cross-selling effectiveness.

9. Credit Card Ownership

    Having a credit card has no significant impact on churn directly.

10. Estimated Salary

    No clear pattern found between salary and churn. Suggests churn is influenced more by engagement than income.

### Recommendation

Based on the analysis, I recommend the following actions:

1.  Engage High-Value Clients Proactively
Use personalized offers, concierge banking, and loyalty programs for customers with high balances.

2.  Focus on German Market Retention
Localize solutions, understand cultural needs, and offer region-specific incentives.

3.  Target Inactive Users
Launch re-engagement campaigns, loyalty bonuses, or personalized messaging to reduce inactivity.

4.  Cross-Sell More Products
Encourage customers to adopt multiple services like loans, savings plans, or insurance for stickiness.

5.  Support for Older Clients
Provide tailored financial planning for older customers to address churn among ages 45+.

6.  Gender-Specific Strategies
Explore why females are leaving more and tailor communication, service support, or benefits accordingly.

7.  Implement Predictive Churn Alerts
Develop a churn prediction model using customer behavior data to intervene early.

8.  Improve Onboarding & Support
Simplify product usage and improve user experience during early customer lifecycle stages.

### Conclusion

This bank customer churn analysis reveals that churn is heavily influenced by age, region, account activity, and number of products owned. High-value clients, particularly in Germany and among older demographics, require tailored engagement. By acting on these insights, banks can reduce attrition, improve customer satisfaction, and build a more loyal customer base.
