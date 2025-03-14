# Personal Expense Tracking Dashboard - Power BI

## Overview
This project is a **Power BI dashboard** designed to track **daily expenses** over three months (January, February, and March 2025). The dashboard provides insights into spending patterns, payment methods, and major expense categories.

**Disclaimer:** This report is made purely for fun and learning purposes. Do not depend on it for financial decisions. 😊

## Features
- **Interactive visualizations** to analyze spending trends.
- **KPIs** such as total spending, highest spending category, and average daily spending.
- **Filters** for easy data exploration (Date, Category, Payment Method, UPI App).
- **Custom tooltips** for additional insights.
- **Comparative analysis** of monthly expenses.

## Live Dashboard
You can view the live Power BI report here: [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODJjNTEzOGUtYmM5MS00NDE5LTkyZDItMGM3ZjQxZWVjMmEzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Dataset Details
The dataset contains **270 records** with the following columns:
- **Date**: The date of the expense (Jan–Mar 2025).
- **Category**: Expense type (Rent, Food, Shopping, etc.).
- **Payment Method**: Cash, Card, or UPI.
- **UPI App**: If paid via UPI, which app was used (Google Pay, PhonePe, Paytm, etc.).
- **Amount**: The transaction amount.
- **Notes**: Additional details about the expense.

## Data Cleaning & Transformation
- Converted **Date** column to Date format.
- Removed any missing or duplicate entries.
- Standardized category names for consistency.
- Created **custom columns** for analysis, such as:
  - **Month Name** from Date.
  - **Payment Type Breakdown**.
  - **UPI App Usage Percentage**.

## Visualizations
1. **Bar Chart** - Category-wise spending.
2. **Stacked Area Chart** - Monthly and category-wise spending.
3. **Pie Chart** - Payment method distribution.
4. **Donut Chart** - UPI App spending breakdown.
5. **KPIs** - Total spending, daily average spending, highest spending category.

## KPIs (Key Performance Indicators)
- **Total Spending** for the last 3 months.
- **Highest Spending Day**.
- **Category Spending % of Total**.
- **Average Monthly Spending**.
- **Top 3 Spending Categories**.
- **Payment Method Usage %**.
- **Transactions Per Day**.
- **Budget vs. Actual Analysis**.

## Filters & Interactivity
- **Date Filter** to analyze spending by specific days/months.
- **Category Filter** to drill down into specific spending areas.
- **Payment Method Filter** to compare usage of Cash, Card, and UPI.
- **UPI App Filter** to analyze which app is used most frequently.

## How to Use the Dashboard
1. **Import the dataset** into Power BI.
2. **Clean & Transform the data** using Power Query.
3. **Create visualizations** as outlined above.
4. **Add interactivity** using filters and slicers.
5. **Publish and share** for financial insights.

## Future Enhancements
- Add **budget tracking** to compare planned vs. actual expenses.
- Include **forecasting models** to predict future expenses.
- Implement **alerts and notifications** for overspending.

## Conclusion
This Power BI dashboard provides a **clear, interactive, and insightful** way to track personal expenses over time. It helps users make data-driven financial decisions efficiently.

⚠ **Reminder:** This dashboard was made for learning and fun purposes only. Do not rely on it for actual financial planning! 🚀

