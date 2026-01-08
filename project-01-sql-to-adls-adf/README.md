<img width="1362" height="684" alt="pipeline_run_success" src="https://github.com/user-attachments/assets/d140e9f2-8d36-462f-b3f6-22f7249a702a" />
# Project 01: SQL to ADLS using Azure Data Factory

## Overview
This project demonstrates an end-to-end Azure Data Engineering pipeline where data is ingested from Azure SQL Database and loaded into Azure Data Lake Storage Gen2 using Azure Data Factory.

## Architecture
Azure SQL Database → Azure Data Factory → Azure Data Lake Storage Gen2

## Services Used
- Azure SQL Database
- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2 (ADLS)
- GitHub (for version control)

## Pipeline Details
- Source: Azure SQL Database (salesdb)
- Sink: ADLS Gen2 (raw container)
- Activity: Copy Data
- Trigger: Scheduled (Daily)

## Key Learnings
- Creating SQL tables and handling duplicate data
- Designing ADF pipelines
- Working with datasets and linked services
- Publishing and triggering pipelines
  
## Pipeline Execution Result
Below screenshot shows successful execution of Azure Data Factory pipeline <img width="1362" height="684" alt="pipeline_run_success" src="https://github.com/user-attachments/assets/aff2e787-c7c1-4360-b728-6d6dcce72716" />
that ingests data from Azure SQL Database into Azure Data Lake Storage Gen2.
