# End-to-End Medallion Data Pipeline using Databricks

## Project Overview

This project demonstrates the implementation of a Medallion Data Pipeline for a telecommunications business scenario using Databricks, Delta Lake and dbt. The pipeline follows the Bronze, Silver and Gold architecture to ingest, clean, transform and prepare customer and transaction data for business reporting and analytics.


## Business Scenario

TelcoPay Australia required a modern data pipeline to improve reporting accuracy. Raw customer and transaction data contained multiple data quality issues, resulting in inconsistent business reports. The objective was to build a scalable Medallion Architecture that produces reliable, analytics-ready data while supporting governed data transformation using dbt. :contentReference[oaicite:1]{index=1}


## Technologies Used

- Databricks
- Delta Lake
- SQL
- dbt (Data Build Tool)


## Project Workflow

### Bronze Layer
- Ingested raw customer and transaction CSV files into Delta tables.
- Preserved source data without modifications.

### Silver Layer
- Identified and resolved data quality issues.
- Removed duplicate records.
- Standardised data formats.
- Applied appropriate data cleansing and validation.

### Gold Layer
- Created business-ready aggregated tables.
- Generated customer spending summaries.
- Produced analytical datasets for reporting and visualisation.

### dbt Integration
- Developed staging and mart models.
- Implemented schema tests.
- Generated a dbt lineage DAG to support governed and maintainable data transformations.



## Skills Demonstrated

- Data Engineering
- ETL Pipeline Development
- Data Warehousing
- Data Cleaning
- Data Quality Assessment
- SQL
- Delta Lake
- dbt
- Databricks
- Business Analytics



## Key Outcomes

- Built a complete Bronze, Silver and Gold Medallion Architecture.
- Improved data quality through systematic cleansing and standardisation.
- Developed analytics-ready datasets for business reporting.
- Implemented dbt models and automated data quality tests to support maintainable data pipelines.



## Author

**Yeshani Dissanayake**

Master of Business Analytics (Data Science)

La Trobe University 
