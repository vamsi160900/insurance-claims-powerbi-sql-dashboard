# Insurance Claims Analytics Dashboard

## Project Overview

This project is a Power BI dashboard built using insurance claims data. The goal is to analyze claim volume, claim amount, fraud status, incident types, customer demographics, and state-level claim trends.

The project uses SQL Server Express as the local database, Power BI Desktop for dashboard development, Power Query for data cleaning, and DAX for KPI calculations.

## Tools Used

- Power BI Desktop
- SQL Server Express
- SQL Server Management Studio
- Power Query
- DAX
- SQL
- CSV Dataset

## Project Workflow

1. Imported insurance claims CSV data into SQL Server Express.
2. Created an insurance claims database in SQL Server.
3. Validated the loaded data using SQL queries.
4. Connected Power BI Desktop to SQL Server.
5. Cleaned and transformed the data in Power Query.
6. Created DAX measures for key business KPIs.
7. Built a 3-page interactive Power BI dashboard.

## Dashboard Pages

### 1. Executive Summary

This page gives a high-level overview of the claims data.

Key visuals:
- Total Claims
- Total Claim Amount
- Average Claim Amount
- Fraud Reported Rate
- Claim Amount by Incident Type
- Fraud Status Donut Chart
- Monthly Claims Trend
- Slicers for Claim Status, Incident Type, and Incident State

### 2. Claims Deep Dive

This page provides detailed claim analysis.

Key visuals:
- Total Claims by Incident Type
- Total Claim Amount by Incident State
- Fraud Status by Incident Type
- Claim Details Table

### 3. Customer Insights

This page shows customer-level claim patterns.

Key visuals:
- Total Claims by Age Group
- Total Claim Amount by Gender
- Total Claim Amount by Education Level
- Average Customer Age
- Total Claims by Occupation
- Slicers for Gender, Education Level, and Claim Status

## SQL Work

SQL was used to validate and analyze the data before building the dashboard.

SQL checks included:
- Row count validation
- Null value checks
- Duplicate policy number checks
- Claim amount summaries
- Fraud vs not fraud analysis
- Monthly claim trends
- Claim amount by state and incident type

## Power Query Work

Power Query was used to clean and prepare the data.

Transformations included:
- Removed empty columns
- Fixed data types
- Created Claim Status column
- Created Age Group column
- Prepared the dataset for reporting

## DAX Measures

The dashboard uses DAX measures such as:

- Total Claims
- Total Claim Amount
- Average Claim Amount
- Fraud Reported Claims
- Not Fraud Claims
- Fraud Reported Rate
- Not Fraud Rate
- Average Customer Age

## Key Insights

- Most claims are related to vehicle collisions.
- Claim amounts vary by incident type and state.
- Fraud reported claims can be analyzed by customer and incident details.
- Customer demographics such as age group, gender, education level, and occupation help explain claim patterns.

## Project Files

- `Insurance_Claims_Dashboard.pbix` - Power BI dashboard file
- `.sql` files - SQL validation and business analysis scripts

## How to Open the Project

1. Download the `.pbix` file.
2. Open it using Power BI Desktop.
3. Review dashboard pages and DAX measures.
4. Open the SQL files in SQL Server Management Studio to review validation and analysis queries.

## Project Purpose

This project was created as a portfolio project to demonstrate skills in Power BI, SQL, Power Query, DAX, data cleaning, data validation, and dashboard reporting.
