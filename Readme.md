# NovaPay FinTech Transaction Analytics

## Project Overview

NovaPay is a fictional financial technology company. This project uses MySQL and Power BI to analyze customer accounts and transaction activity, with a focus on transaction status, account balances, and successful transaction value.

## Tools & Technologies

**MySQL 8.0** — database design, SQL queries, joins, common table expressions (CTEs), window functions, and views.

Power BI Desktop — interactive dashboard, KPI cards, charts, slicers, and a decomposition tree.

### Database Structure

The project uses three core tables:

Customers — customer details and city.

Accounts — account types and balances.

Transactions — transaction amounts, dates, types, and statuses.

The vw_NovaPayAccountAnalytics SQL view combines customer and account information with transaction summaries for analysis in Power BI.

## Dashboard Highlights

Total transaction count

Successful, failed, and pending transaction counts

Successful transaction value

Transaction success rate

Customer account balance comparison

Transaction amount trend

Transaction status breakdown

Customer performance analysis using the SQL view

Decomposition tree for exploring transaction value by city, customer, and account type

### Key Findings

Based on the sample dataset:

20 transactions were recorded.

16 transactions were successful.

2 transactions failed.

2 transactions were pending.

Total transaction amount was $6,090.

Successful transaction value was $5,480.

Transaction success rate was 80%.

## Project Files

Novapay_SQL_project.SQL — MySQL database and analytical SQL scripts.

Novpay_fintech_analytics.pbix — Power BI report.

## How to Explore

Review the SQL script to understand the database and analytical queries.

Open the Power BI report in Power BI Desktop.

Explore the KPI cards, charts, slicer, and decomposition tree.

## Disclaimer

NovaPay and all sample customer and transaction data in this project are fictional. This project is for educational and portfolio purposes only.
