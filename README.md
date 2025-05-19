# Customer Churn Analysis to Develop Retention Strategies

## Overview
This project explores customer churn patterns hidden within the customer database of Databel, a telecommunications company. Through data analysis and interactive visualizations, the goal was to uncover the key drivers of churn and provide actionable insights to support data-informed retention strategies.

## Objective
To identify the factors most strongly associated with customer churn and recommend practical strategies that could help the company reduce churn and improve customer retention.

## Dataset
  - Source: Received from Databel
  - Format: .xlsx (converted and cleaned for Excel analysis)
  - Features include: Customer demographics, services subscribed, billing methods, contract details, and churn status.

## Tools Used
  - Microsoft Excel
    - Data Cleaning & Transformation
    - Pivot Tables for Aggregation & Grouping
    - Logical & Lookup Functions (e.g., IF, VLOOKUP, COUNTIFS)
    - Statistical Functions (e.g., AVERAGEIFS, STDEV.P)
    - Conditional Formatting for quick visual cues
  - Data visualization: Column charts, pie charts, boxplots, heatmaps (simulated), and dynamic slicers for visual exploration

## Analytical Workflow / Methodology
  - Data Preparation:
    - Cleaned blank/invalid entries (e.g., TotalCharges) and ensured data types were appropriately formatted.
    - Mapped churn values into binary (Yes = 1, No = 0) for aggregation.
  - Exploratory Analysis:
    - Calculated overall churn rate and segmented churn across contract types, payment methods, tenure groups, and service features.
    - Used pivot tables and conditional logic to group customers by key characteristics (e.g., senior status, internet service type).
  - Data Visualization:
    - Created charts to visualize churn distribution by customer segment (e.g., tenure, contract, service usage).
    - Developed an interactive dashboard to explore churn behavior with filters (e.g., by gender, contract type).

## Key Insights
  - Overall Churn Rate: Approximately 26.5%, indicating a significant portion of customers are leaving.
  - Tenure: Customers in their first 2 years show the highest churn, while long-term customers (5+ years) are more stable.
  - Contract Type: Month-to-month contracts had the highest churn, compared to 1- or 2-year agreements.
  - Internet Service Type: Fiber optic users churned more than DSL or customers without internet services.
  - Online Security Services: Customers without online security features churned more often.
  - Payment Method: Customers paying via electronic check had the highest churn rate, while credit card users had the lowest.
  - Monthly Charges: Higher monthly charges correlate with increased churn.

## The Customer Retention Strategy
The analysis reveals that customers on month-to-month contracts, those in their early tenure stages, and users of fiber optic services or electronic checks are more likely to churn. A smart retention strategy involves promoting long-term contracts through loyalty incentives and targeting early-tenure customers with onboarding perks or exclusive discounts to increase stickiness. Additionally, bundling valuable services like online security can enhance perceived value and reduce churn risk, especially among high-paying customers. Transitioning users toward more stable payment methods like credit cards via micro-incentives also supports customer longevity. By combining these insights with business intelligence best practices—such as customer lifecycle mapping, churn risk scoring, and personalized retention campaigns—organizations can shift from reactive churn management to proactive customer success, ultimately boosting lifetime value and operational efficiency.
