# Credit_Card_dashboard_Report

Credit Card Analytics Dashboard (Power BI)
Project Overview

This project implements an end-to-end Credit Card Analytics solution using Power BI, designed to analyze customer demographics and credit card transaction behavior. The solution follows a structured business intelligence workflow, including data modeling, DAX-based calculations, and interactive dashboard development.

The primary goal of the project is to transform raw customer and transaction data into actionable insights through well-defined KPIs, optimized visuals, and dynamic filtering, while maintaining analytical accuracy and professional dashboard design standards.

Data Sources and Modeling

The analysis is based on two structured datasets:

Customer Table

Contains customer-level attributes including:

🔹Demographic information

🔹Income group classification

🔹Education level

🔹Asset ownership indicators

🔹Credit utilization metrics

Transaction Table

Contains transaction-level attributes including:

🔹Spending category

🔹Transaction amount

🔹Interest earned

🔹Average utilization ratio

🔹Transaction mode

A one-to-many relationship is established between the Customer and Transaction tables using a unique customer identifier (Client_Num). This relationship enables correct aggregation, drill-down, and cross-filtering across both dashboards.

Dashboard Architecture

The Power BI report consists of two dedicated analytical dashboards:

1. Credit Card Customer Report

This dashboard focuses on customer profiling and segmentation.

Key KPIs

🔹Total Customers: Distinct count of active customers

🔹Average Age: Mean customer age across the filtered dataset

🔹Average Credit Utilization Ratio: Average utilization of credit limits

Analytical Visuals

🔹Customer distribution by Age Group (derived using DAX)

🔹Customer distribution by Income Group (derived using DAX)

🔹Customer distribution by Education Level

🔹Asset Ownership Analysis to compare ownership patterns across customers

Interactivity

🔹Slicers for Gender, Age Group, and Income Group

🔹Dynamic cross-filtering across all visuals for segmented analysis

This dashboard supports demographic analysis and identification of dominant customer segments.

2. Credit Card Transaction Report

This dashboard focuses on spending behavior and revenue-related analysis.

Key KPIs

🔹Total Transaction Amount: Aggregated transaction value

🔹Total Interest Earned: Revenue generated from credit card usage

🔹Total Customers: Customer base contributing to transactions

Analytical Visuals

🔹Transaction amount by Spending Category

🔹Interest contribution by category using a Treemap to represent proportional revenue distribution

🔹Transaction Mode Distribution (e.g., chip, swipe, online)

🔹Average Transaction Amount by Category to compare transaction value intensity

This dashboard enables identification of high-value spending categories, revenue-driving segments, and customer transaction preferences.

DAX Calculations and Logic

The following DAX techniques were applied during development:

Calculated Columns

🔹Age Group classification

🔹Income Group classification

Measures

🔹Aggregated KPIs for transaction amount, interest earned, and customer count

🔹Average-based metrics for utilization and transaction values

DAX logic was implemented with a focus on correct aggregation behavior, filter context awareness, and performance efficiency.

Design and Visualization Considerations

🔹KPIs were selected strictly based on available and reliable data to avoid misleading insights

🔹Redundant or analytically unsupported metrics were intentionally excluded

🔹Appropriate visual types were chosen to ensure each chart communicates a distinct analytical purpose

🔹Visual alignment, spacing, and formatting were optimized to achieve an executive-ready dashboard layout

🔹Binary indicator fields were avoided in visuals to improve interpretability

Project Structure

Power BI Report

🔹Data Model and Relationships

🔹DAX Measures and Calculated Columns

🔹Interactive Visualizations

🔹Final Dashboard Layout

Tools and Technologies

🔹Power BI

🔹DAX

🔹Power Query

🔹Microsoft Excel

Conclusion

This project demonstrates a complete Power BI analytics workflow, from data modeling and DAX calculations to professional dashboard design. The final solution provides a technically sound and business-focused view of credit card customer and transaction data, supporting both high-level decision-making and detailed analytical exploration.

Author
Devang Magare
Aspiring Data Analyst | Power BI
