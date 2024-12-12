# Data Processing Pipeline

This project demonstrates a data pipeline for extracting, transforming, and visualizing data from an API using Azure cloud services. The pipeline architecture is as follows:

## Pipeline Overview


1. **Data Extraction**:
   - Use an API to extract raw data. Data is ingested using Azure Data Factory pipelines.

2. **Data Transformation**:
   - Process raw data in Azure Databricks using PySpark or SQL.
   - Perform ETL (Extract, Transform, Load) operations to prepare the data for analysis.

3. **Analytics and Visualization**:
   - Load transformed data into Azure Synapse Analytics for querying.
   - Connect Synapse to Power BI, Looker Studio, or Tableau for dashboard creation.

## Technologies Used

- **Azure Data Factory**
- **Azure Data Lake Gen2**
- **Azure Databricks**
- **Azure Synapse Analytics**