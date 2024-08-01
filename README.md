# DataScienceAIMLOps-Platforms-Tools
DataScience AI MLOps Platforms Tools - Databricks, sagemaker, etc

Databricks is a good tool for building, training and deploying models. Easy to learn and use (1-2 days)
1.	It has useful features like experiment tracking, logging and versioning the best model during training, storing the artifacts in a catalog (cloud dbfs data store)
2.	It allows easy reloading, retraining and redeploying the model
3.	It uses the MLFlow library to perform these activities
4.	The Unity catalog acts as a versioned data store (metastore, schema, tables, etc) with governance policies and access control
5.	It is flexible in connecting with different cloud providers (AWS, Google , etc) to get access to compute and storage (cloud buckets)
6.	Both data and models can be easily read/written from/to the cloud using their API calls
7.	One main thing to remember is that you still need to know how to build, train, tune models, i.e. the data science process
8.	Databricks can’t build the model for you. It’s a tool to simplify the MLOps process and provide all the audit, governance, policy features in one connected platform
9.	It provides ready made connectors to data lakes and warehouses like Snowflake, to for easy data ingestion and other data engineering activities
10.	I am giving a sample code notebook for building, training, tuning and deploying a regression model for predicting a disease using synthetic data 
11.	This can be easily extended to different models, hyperparameter tuning, deploying, etc
