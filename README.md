# Data-Pipeline-for-NYC-Yellow-Taxi-datasheet

Building a Data Pipeline and Creating Reporting Tables using NYC Yellow Taxi Dataset

In this phase of the assignment, you will focus on ingesting 1 million rows of data from the NYC Yellow Taxi dataset provided to you. The goal is to create a robust data pipeline that can efficiently handle and store the dataset for subsequent analysis. You are required to perform the following tasks:

Download and Familiarize: Download the NYC yellow_tripdata_2016-02 dataset and become familiar with its structure and attributes. Understand the data better via the data dictionary here 

2. Data Transformation: Perform basic data transformation tasks, such as handling data type conversions, to ensure the ingested data is ready for analysis. 

3. Data Ingestion: Implement a data ingestion process to load 1 million rows of data from the dataset into your Postgres database system. Ensure that the ingestion process is efficient and can handle large volumes of data.


In this phase, you will utilise the ingested data to build reporting pipelines that generate valuable insights from the NYC Yellow Taxi dataset. You will create three reporting tables as described below: 

PHASE II Instructions operations_and_performance 

1. How many trips were recorded in the dataset?
 
2. What is the average trip distance for all trips?
 
3. Which Vendor has the highest number of trips?
 
4. Which Vendor has the lowest number of trips?
   
5. What is the average passenger count per trip? 

customer_demographics_and_preferences 
1. What is the average trip amount given by passengers?
   
2. What is the average trip distance by passengers?
   
3. How many trips were flagged as 'store and forward'?
   
4. How many trips were shared rides (passenger count > 1)? 

 shared_ride_count financial_performance 

1. What is the average fare amount per trip? 

2. How much revenue was generated from tolls and surcharges combined? 

3. What is the average total amount paid by passengers? 
