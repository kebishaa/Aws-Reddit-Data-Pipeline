# Data Pipeline with Reddit, AWS Glue, Airflow, Celery, Postgres, S3,  Athena, and Redshift
This project offers a full-featured ETL pipeline for Reddit data, designed to efficiently handle data ingestion, transformation, and loading into Amazon Redshift. It combines the strengths of Apache Airflow, Celery, PostgreSQL, S3, AWS Glue, and Athena for optimal performance and scalability.

# Summary of Contents
## . Overview
## . Architecture
## . Prerequisites
## . System Setup

# Overview
The pipeline is designed to:

1. Extract data from Reddit using its API.
2. Store the raw data into an S3 bucket from Airflow.
3. Transform the data using AWS Glue and Amazon Athena.
4. Load the transformed data into Amazon Redshift for analytics and querying.

# Architecture

![Architecture](https://github.com/kebishaa/Aws-Reddit-Data-Pipeline/blob/main/assets/RedditDataEngineering.png?raw=true)!

1. Reddit API: Source of the data.
2. Apache Airflow & Celery: Orchestrates the ETL process and manages task distribution.
3. PostgreSQL: Temporary storage and metadata management.
4. Amazon S3: Raw data storage.
5. AWS Glue: Data cataloging and ETL jobs.
6. Amazon Athena: SQL-based data transformation.
7. Amazon Redshift: Data warehousing and analytics.
