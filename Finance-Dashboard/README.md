# Finance Performance Dashboard – Power BI

## Business Problem
The finance team needs a clear and interactive dashboard to monitor revenue,
expenses, projects, vendors, and payment methods across different regions and
departments. The goal is to support management in understanding financial
trends and operational performance.

## Dataset Overview
The dataset contains financial transaction records with the following fields:
- Date
- Department
- Region
- City
- Project
- Vendor
- Expense Category
- Payment Method
- Currency
- Revenue
- Amount (Expenses)
- Approval Status

Basic data cleaning and formatting were applied before building the dashboard.

## Data Model
- Single fact table: Finance_data
- Flat structure optimized for aggregation
- Date hierarchy enabled (Year, Quarter, Month, Day)

## Key KPIs
- Total Revenue
- Total Expenses
- Number of Projects
- Number of Vendors

## Dashboard Visuals
- Revenue by Project
- Number of Projects by Region
- Revenue by Payment Method
- Monthly Revenue Trend
- Revenue by City (Map)
- Interactive slicers by Currency and Department

## Tools Used
- Power BI
- Power Query
- DAX
- Data Modeling

## Key Insights
- Revenue is driven by a small number of high-performing projects.
- Some regions have high project volume but lower revenue contribution.
- Credit Card and Cheque are dominant payment methods.
- Monthly revenue shows clear fluctuations indicating seasonality.

## Portfolio Value
This dashboard demonstrates KPI-driven analysis, clean data modeling,
and business-focused storytelling using Power BI.
