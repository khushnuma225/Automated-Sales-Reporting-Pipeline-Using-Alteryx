## Automated-Sales-Reporting-Pipeline-Using-Alteryx
### Project Overview
This project demonstrates an end-to-end sales analytics and automated reporting workflow built using Alteryx.
The objective was to work with raw, messy data, perform data preparation, generate multiple KPIs and charts, and deliver a business-ready consolidated report.

The project simulates a real-world reporting scenario commonly used in analytics teams.

### Data Description

The project uses 3 raw datasets (10,000+ records):

**Customers Data**
**Sales Transactions Data**
**Product Data**

### Tools & Technologies

* Alteryx Designer
* Data Cleansing Tool
* Join Tool
* Summarize Tool
* Formula Tool
* Reporting Tools (Table, Charting)
* Union Tool
* Layout & Render Tool

### Workflow Design

* Data Ingestion
* Loaded raw CSV datasets into Alteryx
* Data Preparation
* Handled missing values and duplicates
* Standardized text fields and formats
* Data Integration
* Joined Customers, Products, and Sales datasets

### KPI & Analysis Streams

* Total Revenue
* Total Orders
* City-wise Sales Performance
* Sales Channel Analysis
* City-wise Revenue
* Channel-wise Sales Distribution

### Reporting & Automation

* Converted KPIs and charts into reporting objects
* Combined multiple reporting streams using Union
* Designed final layout using Layout tool
* Generated a consolidated PDF report using Render
* Controlled parallel execution using Block Until Done
* Enabled automated email distribution logic.

### Output
* Excel Report – KPI tables and cleaned datasets
* PDF Report – Consolidated KPIs and visual charts for stakeholders
### Workflow Preview
<img width="1866" height="967" alt="Alt_sales_reporting" src="http://github.com/user-attachments/assets/d5b75c86-7cec-4f59-92fb-8b167a6cf5c6"/>
