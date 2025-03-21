# Sales and Finance Analytics in Excel

In order to provide Atliq Hardware Technologies with insights into its financial health and sales success, this project uses Excel to create an extensive range of reports. The project offers useful metrics for decision-making by utilizing Power Query, Power Pivot, and Data Modeling.

---

## Table of Contents

1. [Introduction](#Introduction)
2. [Highlights](#Highlights)
3. [Resources and Methodology](#Resources-and-Methodology)
4. [Sales Analytics Goals](#Sales-Analytics-Goals)
5. [Finance Analytics Goals](#Finance-Analytics-Goals)
6. [Workflow Summary](#workflow-breakdown)
7. [Role of Reports](#role-of-reports)
8. [Documentation](#documentation)
9. [References](#references)

---

## Introduction

The aim of this project is to create an analytical system that enables detailed exploration of sales and financial data for Atliq Hardware Technologies. It includes analyzing market performance, customer buying behavior, and profit & loss details by various dimensions such as regions, months, and fiscal periods

---

## Highlights
- Sales Analytics:
  - Market Performance Report
  - Customer Performance Report
- Finance Analytics:
  - P&L Statements by 
    - Market,
    -  Month, 
    -  and Fiscal Year

---

## Resources and Methodology
- The analysis uses CSV files provided by Atliq Hardware Technologies:
  - dim_customer.csv: Customer details.
  - dim_product.csv: Product information.
  - dim_market.csv: Market segments.
  - fact_sales_monthly.csv: Monthly sales
  - target.csv: Market performance benchmarks.

- Excel Features:
  - Power Query for data cleaning and transformation.
  - Data Model for relationship building between tables.
  - Power Pivot for calculated measures.
  - User-friendly and visually enhanced reports.

---

## Sales Analytics Goals

The Sales Analytics section was designed to offer detailed insights into the performance of markets and customers for Atliq Hardware Technologies, with a focus on:
- Identifying top-performing markets and tracking their sales against benchmarks.
- Understanding customer behavior, including purchasing patterns, repeat orders, and overall contribution to sales.

These insights help refine sales strategies by highlighting top contributors and areas needing improvement.

---

## Finance Analytics Goals

The Financial reports provide a detailed overview of Atliq's fiscal health, focusing on:
- Profit and Loss statements, helping to track revenue and costs across different markets.
- Time-based financial trends, providing insights into financial performance across months and fiscal years.

These reports are essential for decision-makers to monitor financial performance and make informed budgeting and resource allocation decisions.

---

## Workflow Summary

1. Data Loading
   - Imported five CSV files into Power Query: dim_customer, dim_market, dim_product, fact_sales_monthly, and target.

2. Data Cleaning
   - Performed data cleaning in Power Query: removed duplicates, unnecessary columns, and standardized formats.

3. Data Modeling
   - Created relationships between tables in the Data Model, added a Dim Date table, and connected tables for accurate reporting.

4. Data Analysis
   - Used Power Pivot and DAX to calculate key metrics such as total revenue, market performance, and target vs. actual sales.

5. Report Creation
   - Developed interactive reports:

     - Customer Performance Report: Analyzed customer behavior and sales contributions.
     - Market Performance Report: Compared sales performance to targets.
     - P&L Reports: Provided financial insights segmented by market, month, and fiscal year.

---

## Role of Reports

The reports in this project play a crucial role in guiding decision-making for Atliq Hardware Technologies:
- Customer Performance Report: 
  - This report helps stakeholders focus on customer-specific strategies by identifying high-value customers and tracking their purchasing behavior over time.
- Market Performance Report: 
  - Enables the business to monitor market success and identify which regions or market segments are meeting or exceeding their sales targets.
- P&L Statements:
  - These reports are essential for financial planning and control, helping the business track profitability and make adjustments in real time based on market or temporal factors.

---

## Documentation

Check out all the created reports that I have attached to this repository.
- [Customer Performance Report](https://github.com/VASU12122001/Excel-Sales-Analytics/blob/main/Customer%20Performance%20Report.pdf)_
- [Market Performance Report](https://github.com/VASU12122001/Excel-Sales-Analytics/blob/main/Market%20Performance%20vs%20Target%20Report.pdf)_
- [P&L Statement By Market Report](https://github.com/VASU12122001/Excel-Sales-Analytics/blob/main/P%26L%20Statement%20by%20Markets.pdf)_
- [P&L Statement By Year Report](https://github.com/VASU12122001/Excel-Sales-Analytics/blob/main/P%26L%20Statement%20by%20Fiscal%20Year.pdf)_
- [P&L Statement By Month Report](https://github.com/VASU12122001/Excel-Sales-Analytics/blob/main/P%26L%20Statement%20by%20Months.pdf)_

---

## References

This project is part of a "Excel: Mother of Intelligence" course offered by Codebasics,and it uses Atliq's real-world business data for learning and analysis. For more details, visit the Codebasics website: [Check Out](https://codebasics.io/courses/excel-mother-of-business-intelligence)



