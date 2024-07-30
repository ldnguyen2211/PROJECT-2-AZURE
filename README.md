## Project Azure 2: Movie Recommender System on Azure

# 1. Overview
This project demonstrates how to build a movie recommender system using Python and Spark on Microsoft Azure. We’ll analyze the Movielens dataset and deploy the system using Azure Data Factory and Azure Databricks.

# 2. Agenda
   
a. Download the Movielens dataset from the Grouplens website: 
+ Explore movie names, ratings, links, and tags.

b. Azure Setup
+ Create an Azure subscription.
+ Organize resources into a resource group.
+ Set up a standard storage account and a standard storage blob account.
  
c. Data Preparation
+ Upload the Movielens zip file dataset to the standard storage blob account.
  
d. Azure Data Factory and Data Pipelines
+ Set up an Azure Data Factory.
+ Create a copy data pipeline to transfer data from Azure blob storage to Azure Data Lake storage.
  
e. Working with Databricks
+ Create a Databricks workspace.
+ Access Azure Data Lake storage from Databricks.
+ Extract the zip file and obtain CSV files.
  
f. Data Analysis with Spark
+ Read datasets into Spark dataframes in Databricks.
+ Analyze the dataset to derive movie recommendations.
