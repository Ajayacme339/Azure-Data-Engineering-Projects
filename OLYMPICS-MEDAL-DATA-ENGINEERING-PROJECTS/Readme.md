### Azure Data Engineering 2021 OLYMPICS Medal Project 

### Overview 
This Project aims to perform End to End Data engineering on 2021 OLYMPICS Medal Dataset and generate insights from it.We will be using different 
data taechnology to ingest,process,transform and load data into datawarehouse.
### Project Goals 
  1.Data Ingestion - Build a Pipeline to Ingest data from 2021 Olympics csv dataset 
  
  2.Data Pipeline - Build a Data Pipeline to extract data from Github API and Load it to Data Lake storage
  
  3.Data Processing, Cleansing and Transformation - Process , Cleanse and Transform Data in Azure DataBricks 
  
  4.Storage ,Query and Analytics - Load Transformed Data from Datalake to snowflake Datawarehouse for Storage,Query and Analytics.
### Architecture Diagram 
![Screenshot 2024-02-12 201402](https://github.com/Ajayacme339/AzureDataEngineeringProjects/assets/60890279/0a1c5fa7-dd67-4dbc-8d5d-cd29de8a468e)

### Modern Data Stack Technology used 
 - Azure Data Factory - Data Orchestration and Ingestion from Githbu API - Azure DataLake Gen2 Storage.Pipeline building to copy data to Datalake
   
 - Azure Data Lake Storage - Data Storage for 2021 Olympics csv Dataset . 2 Seperate Container were used to store raw and transformed 2021 Olympics csv Dataset
   
  - Azure Databricks - Data Processing and Tranformation was done on Azure Databricks Platform
    
 - Python Pandas Library - Data Cleansing and Transformation
   
 - Apache Spark - Data Transformation and copy back transformed data to Datalake
   
 - Snowflake - Storage and running analytical query on 2021 Olympics csv Dataset

### Datset Used for This Project can be Found at Below Mentioned Link
  - https://raw.githubusercontent.com/Ajayacme339/AzureDataEngineeringProjects/main/OLYMPICS-MEDAL-DATA-ENGINEERING-PROJECTS/Athletes.csv



 

