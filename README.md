# Retail Analytics Dashboard – Power BI Project
### Project Overview

This project is an end-to-end Retail Analytics Dashboard built using Power BI. The objective was to integrate multiple raw data sources, design a robust data model, implement DAX calculations, and generate actionable business insights through interactive visualizations.

The dataset consisted of multiple disparate files including Sales data, Product mapping, City Tier information, and Pin Code geography data. The final deliverable is a business-ready dashboard that provides multi-dimensional analysis of retail performance.

### Dataset Description

The project uses the following datasets:

Sales Data – Transaction-level sales records

Product Map – Product category and group mapping

City Tier Data – City classification details

PinCode Geo Data – Geographic zone information

These datasets were integrated into a unified Power BI data model.

### Data Preparation & Modeling

Imported multiple raw files into Power BI

Cleaned data by handling missing values (Zone, City Tier)

Standardized city names for consistency

Created relationships between tables (City, Product, Zone, etc.)

Ensured referential integrity across the model

The data model was structured to support scalable reporting and accurate aggregations.

### DAX Calculations Implemented

Several calculated columns and measures were created using DAX:

Net Units = Units – Cancelled Units

OrderDayOfWeek – Extracted weekday name from order date

OrderWeekStart – Week start date (Monday-based weekly trend analysis)

KPI Measures:

Total Revenue

Total Quantity

Total Cancellations

Number of Customers

Number of Transactions

These calculations enabled advanced time-based and performance analysis.

### Dashboard Features

The final dashboard includes:

Revenue & Quantity trends (Monthly & Weekly)

Weekday vs Weekend performance analysis

Product Group performance insights

City, Zone & City Tier-level analysis

Customer and transaction metrics

Interactive filters and slicers for dynamic reporting

### Key Skills Demonstrated

Power BI Data Modeling

Relationship Management

DAX (Calculated Columns & Measures)

Time Intelligence

Data Cleaning & Transformation

KPI Dashboard Design

Business Insight Generation

### Business Value

This dashboard helps stakeholders:

Identify high-performing product groups

Compare weekday vs weekend sales behavior

Analyze geographic performance trends

Track revenue, cancellations, and customer activity

Make data-driven retail decisions

### Files Included

Retail_Case_Study.pbix – Main Power BI dashboard file

Raw datasets (CSV & Excel files)

Project documentation

### Tools Used

Power BI Desktop

DAX

Excel
