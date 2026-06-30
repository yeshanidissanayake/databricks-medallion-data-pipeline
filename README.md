# databricks-medallion-data-pipeline
End-to-end Medallion Data Pipeline using Databricks, Delta Lake and dbt.
# End-to-End Medallion Data Pipeline using Databricks

## Project Overview

This project demonstrates the design and implementation of an end-to-end Medallion Data Pipeline using Databricks, Delta Lake and dbt for TelcoPay Australia. The project follows the Medallion Architecture (Bronze, Silver and Gold layers) to transform raw customer and transaction data into clean, reliable and analytics-ready datasets.


## Business Problem

Telecommunication companies manage large volumes of customer and transaction data that often contain missing values, duplicates and inconsistent formats. These data quality issues affect reporting accuracy and business decision-making.

The objective of this project was to build a scalable data pipeline that cleans, transforms and organises the data to improve reporting and support business insights.


## Technologies Used

- Databricks
- Delta Lake
- SQL
- dbt (Data Build Tool)
- Azure Databricks


## Medallion Architecture

### Bronze Layer
- Loaded raw customer and transaction datasets
- Preserved original data

### Silver Layer
- Removed duplicates
- Handled missing values
- Standardised data formats
- Improved data quality

### Gold Layer
- Created business-ready datasets
- Generated customer spending summaries
- Produced reporting tables for business analysis



## Skills Demonstrated

- Data Engineering
- ETL Pipeline Development
- Data Cleaning
- Data Quality Assessment
- SQL
- Delta Lake
- dbt
- Data Warehousing
- Business Analytics


## Key Outcomes

- Built an end-to-end Medallion Architecture
- Improved data quality through transformation processes
- Created analytics-ready datasets for reporting
- Implemented dbt models to improve data pipeline management



## Author

**Yeshani Dissanayake**

Master of Business Analytics (Data Science)
La Trobe University
