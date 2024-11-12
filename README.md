# Data Migration from to Azure Databricks

## Introduction 
This project involves migrating data from an Oracle database into Databricks, validating the data post-migration, and performing an analysis to ensure consistency with pre-migration analysis. Following the analysis, the data is encrypted to ensure security.

## Project Workflow
1. Data Migration from Oracle to Databricks
The project begins with the extraction of data from the Oracle database. The data is then loaded into Databricks using a secure and efficient method to ensure minimal data loss or corruption.
2. Data Validation
After migration, the data is validated against the original data in the Oracle database. This step involves comparing key metrics and values from the source and destination databases.
Manual checks are employed to ensure the integrity and accuracy of the migrated data.
4. Pre-Migration Analysis Comparison
A comparison is made between the analysis performed on the Oracle data and the data after migration to Databricks.
This ensures that no discrepancies have been introduced during the migration process and that the analysis results remain consistent.
5. Data Analysis in Databricks
Once the data has been successfully migrated and validated, various analytical tasks are performed in Databricks.
These tasks can include data cleaning, exploration, visualization, and complex analytical queries to derive insights from the migrated dataset.
6. Data Encryption
To secure the sensitive data, encryption techniques are applied to the data in Databricks.
