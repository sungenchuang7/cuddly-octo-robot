# data-engineering-notes

## ETL (Extract, Transform, and Load) 
1. Extract data from where it is
2. Transform by getting rid of duplicated data or null values 
3. Loading it into a landing repo 

* Batch Processing - on a given schedule, loading data into ETL pipelines.

* Stream Ingestion - supports streaming data, continuously extracting, transforming and loading data.

## Data Replication
Continuously replicating data into another repository
* Why? 
    1. Redundancy in case a repo goes offline
    2. Apps need to have performant backend computing, which our source data isn't able to support


## Data Virtualization 
Data virtualization is a technology that enables users to access and manipulate data from multiple, heterogeneous sources without requiring physical data movement or replication. It acts as a virtual layer, providing a unified view of data across different databases, applications, and formats. This allows for real-time data access and integration, making it easier to query and analyze data as if it were all in a single location, even though it remains stored in its original source systems.

## How Can We Use the Cleaned Data? 
* Business Intelligence 
* Machine Learning
* Data Warehouse
