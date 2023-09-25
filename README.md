# Healthcare Fraud Detection in New York using Graph Databases
## Overview
This project aimed to uncover potential healthcare fraud activities within New York's healthcare clinics, hospitals, and individual practitioners. By analyzing relationships between these entities, as well as their interactions with patients, we've honed in on patterns indicative of overbilling and unnecessary treatments.

## Dataset
Our primary data sources encompass:

### Inpatient Claims: 
Insights on claims filed for admitted patients, including admission and discharge dates, diagnosis codes, and more.
### Outpatient Claims: 
Details on claims for patients who visited hospitals but were not admitted.
### Beneficiary Details: 
Provides beneficiary KYC details, such as health conditions and region.

The datasets were primarily sourced from Kaggle and were cleaned and preprocessed to fit our analysis requirements.

## Database and Data Ingestion
For this project, we utilized Neo4j, a graph database that enabled us to map and analyze the intricate relationships in our data. We transformed the raw datasets into a structured format suitable for graph representation, defining nodes and relationships pertinent to our fraud detection goals. Once structured, data was ingested into the database using [specific-method/tool, e.g., "Neo4j's CSV Bulk Importer"].

## Exploratory Data Analysis (EDA)
Our EDA process incorporated various methods to understand the underlying patterns and distributions within the data. Some of the techniques applied include:

## Distribution plots for claim amounts to identify outliers.
Frequency analysis of diagnosis codes to recognize unusually common treatments.
Relationship analysis to understand the connectivity and relationships between different healthcare entities.
Through this exploratory approach, we laid a foundation for the subsequent development of our fraud detection algorithms.
