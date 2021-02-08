# Data Engineering Projects

## Project 1: Data Modeling with Postgres
In this project, applied Data Modeling with PostgreSQL and build an ETL pipeline using Python. A startup wants to analyze the data that they have been collecting on songs and user activity on their new music streaming app. Currently, data is collected in JSON format and the analytics team is particularly interested in understanding which songs users are listening to.

Link: [Data_Modeling_with_Postgres](https://github.com/oresttokovenko/Goodreads_ETL/tree/master/Data_Modeling_with_Postgres)

## Project 2: Data Modeling with Cassandra
In this project, I applied Data Modeling with Cassandra and build an ETL pipeline using Python. I built a Data Model around our queries that we want to get answers for. 

For our use case we want to the following: 

 - Obtain details of a song that was herad on the music app history during a particular session. 
 - Obtain songs played by a user during particular session on music app. 
 - Obtain all users from the music app history who listened to a particular song.

Link : [Data_Modeling_with_Apache_Cassandra](https://github.com/oresttokovenko/Goodreads_ETL/tree/master/Data_Modeling_with_Apache_Cassandra)

## Project 3: Data Warehouse
In this project, I applied the Data Warehouse architectures we learned and build a Data Warehouse on AWS cloud. I built an ETL pipeline to extract and transform data stored in JSON format in S3 buckets and move the data to Warehouse hosted on Amazon Redshift. 

Use Redshift IaC script - [Redshift_IaC_README](https://github.com/oresttokovenko/Goodreads_ETL/blob/master/Redshift_IaC_README.md)

Link  - [Data_Warehouse](https://github.com/oresttokovenko/Goodreads_ETL/tree/master/Data_Warehouse)

## Project 4: Data Lake
In this project, I built a Data Lake on AWS cloud using Spark and AWS EMR cluster. The data lake will serve as a Single Source of Truth for the Analytics Platform. We will write spark jobs to perform ELT operations that picks data from landing zone on S3 and transform and stores data on the S3 processed zone.

Link: [Data_Lake](https://github.com/oresttokovenko/Goodreads_ETL/tree/master/Data_Lake)

## Project 5: Data Pipelines with Airflow
In this project, I orchestrated our Data Pipeline workflow using an open-source Apache project called Apache Airflow. I scheduled ETL jobs in Airflow, created project related custom plugins and operators and automate the pipeline execution. 

Link:  [Airflow_Data_Pipelines](https://github.com/oresttokovenko/Goodreads_ETL/tree/master/Airflow_Data_Pipelines)

## Project 6: API Data to Postgres
In this project, I built an ELT pipeline to fetch data from Yelp API and insert it into the Postgres Database. This project is a very basic example of fetching real time data from an open source API.

Link: [API to Postgres](https://github.com/oresttokovenko/Goodreads_ETL/tree/master/Data_Api_to_Postgres)
