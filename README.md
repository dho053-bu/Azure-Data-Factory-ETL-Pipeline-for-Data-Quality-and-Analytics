# Azure Data Factory ETL Pipeline for Data Quality and Analytics

## Overview
This project demonstrates an end-to-end ETL pipeline built using Azure Data Factory to ingest, transform, validate, and structure data for downstream analytics.

The pipeline processes structured datasets, applies data cleaning and validation rules, and loads the data into a format suitable for reporting and analysis.

## Key Features
- Built ETL pipelines using Azure Data Factory
- Ingested and transformed structured datasets from multiple sources
- Implemented data validation and quality checks
- Resolved data issues such as schema mismatches and parsing errors
- Structured data for downstream analytics and reporting
- Developed workflows to improve data reliability and consistency

## Tools & Technologies
- Azure Data Factory
- Azure SQL
- SQL
- Power BI
- Python
- GitHub

## Pipeline Workflow
1. Data is ingested from source systems
2. Data is cleaned and transformed using ADF pipelines
3. Processed data is loaded into structured tables
4. Validation checks ensure data quality and consistency
5. Data is used for analytics and dashboard reporting

## Data Quality & Validation
- Schema validation
- Missing value handling
- Duplicate detection
- Data type consistency checks
- Row count validation

## Repository Structure

```
├── factory/                 # ADF pipeline configurations
├── linkedTemplates/         # ARM template dependencies
├── ARMTemplateForFactory.json
├── ARMTemplateParametersForFactory.json
└── README.md
```

## Results
This pipeline improves data reliability and ensures consistent, high-quality data for downstream analytics and reporting.

## What I Learned
- Building scalable ETL pipelines in Azure Data Factory
- Debugging ingestion and transformation issues
- Implementing data validation and governance practices
- Designing data workflows for analytics-ready datasets

## Pipeline Screenshots

### Pipeline Overview
![Pipeline Overview](docs/pipeline-overview.png)
