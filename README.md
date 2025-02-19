Data Processing Pipeline with GCP and Airflow

This project showcases the implementation of a data processing pipeline using Google Cloud Platform (GCP) and Apache Airflow. 
The pipeline efficiently handles 1 million records by extracting data from Google Cloud Storage (GCS), loading it into BigQuery,
 and transforming it into structured country-specific tables and analytical views.

Key Features
Extracts CSV data from Google Cloud Storage.
Loads raw data into a staging table in BigQuery.
Transforms and organizes data into country-based tables and reporting views.
Utilizes Apache Airflow for seamless orchestration.
Produces structured datasets for insightful analysis.
![394238803-87cdc79c-c9a1-4c4d-887a-ab6007394bc7](https://github.com/user-attachments/assets/a545c810-3368-45a8-b0f7-c133e2ddaf8c)

Workflow Overview

Extract: Verify file availability in GCS.
Load: Import raw CSV data into a staging table in BigQuery.
Transform: Create structured country-specific tables.

Build analytical views for reporting.
Data Layers
Staging Layer: Raw data storage from CSV files.
Transform Layer: Cleaned and structured datasets.
Reporting Layer: Optimized views for analysis.

Required Tools & Services

Google Cloud Platform (GCP)
Google Compute Engine (for Airflow)
BigQuery
Cloud Storage
Apache Airflow
Airflow with Google Cloud integrations


Results : 
<img width="486" alt="Screenshot 2025-02-19 154310" src="https://github.com/user-attachments/assets/90379ce4-268a-435e-a49c-379afbcb64f8" />


<img width="471" alt="Screenshot 2025-02-19 154456" src="https://github.com/user-attachments/assets/1d110973-97af-46ed-bff4-a3cdf8c2bc4d" />



Thank you


Project by : https://github.com/vishal-bulbule


