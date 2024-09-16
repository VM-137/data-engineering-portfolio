# Data Engineering Portfolio

This portfolio is a compilation of code which I have created for data engineering works, projects, examples.

## Data Engineering 101: [![](https://badgen.net/badge/101/examples/black)]()
* #### Denormalizing Tables in Data Warehouse: Creating Materialized Views
  This project demonstrates how to denormalize tables in a data warehouse by creating materialized views to improve query performance for customer analytics. We use a star schema model with fact and dimension tables and build materialized views for optimized data retrieval. This approach showcases core data engineering skills like schema design, denormalization, and the creation of materialized views for high-performance reporting. <br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/datawarehouse-denormalizing-tables-creating-materialized-views)


* #### Data Quality Validation for Data Warehousing
  This project focuses on conducting comprehensive data quality checks within a data warehousing environment. It demonstrates the use of a Python-based framework integrated with PostgreSQL to validate data integrity, ensuring accuracy and consistency. <br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/billing-data-warehouse-quality-check)


* #### Billing Data Warehouse
  This project focuses on designing a **data warehouse** for a cloud service provider using their historical billing data. The goal is to organize this data into a **star schema** that can efficiently support queries related to         billing trends, customer insights, and more.<br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/billing-data-warehouse)

* #### Airflow Simple ETL pipeline<br>
    This repository contains a simple data engineering project that demonstrates how to build an ETL pipeline using Apache Airflow. The project processes road traffic data from various toll plazas, consolidating data from different       formats into a single, transformed CSV file.<br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/ETL-PIPELINE-AIRFLOW)
    
* #### Flask Continuous Deployment with GCP<br>
    Example of deploying a Flask web application with continuous deployment using PaaS and Google App Engine. <br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/cd-on-gcp-flask-web-)

* #### Demo Multi Cloud Continuous Integration Github Actions<br>
    Simple demo of continous integration using Github Actions to perform tests using AWS, Azure or GCP <br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/demo-multi-cloud-continuous-integration-github-actions-)

* #### Testing Techniques<br>
    This is a repo for doing a simple example of testing python code<br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/testing-techniques)


## AWS:
* #### AWS end-to-end Youtube Analysis Project<br>
    AWS Services used: (Amazon S3, AWS IAM, QuickSight, AWS Glue, AWS Lambda, AWS Athena)<br>
    Project Goals:
    * Data Ingestion — Build a mechanism to ingest data from different sources
    * ETL System — We are getting data in raw format, transforming this data into the proper format
    * Data lake — We will be getting data from multiple sources so we need centralized repo to store them
    * Scalability — As the size of our data increases, we need to make sure our system scales with it
    * Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
    * Reporting — Build a dashboard to get answers to the question we asked earlier<br>
      
    [![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/end_to_end_youtube_data_analysis)

* #### AWS Serverless AI Data Engineering Pipeline<br>
    This is an example of a Serverless AI Data Engineering Pipeline.<br>
    AWS Services used: (DynamoDB, Lambda, SQS, CloudWatch, Comprehend, S3)<br>
With CloudWatch Timer we will invoke a AWS Lambda function(Producer) that reads a DynamoDB table and send each item as a message to a SQS queue, when a message feeds the queue a trigger will invoke a AWS Lambda function(Consumer) that will perform a request to Wikipedia API and ask for the first result and the first 2 lines of the content, then we will perform a sentiment analysis using AWS Compehend and store the results in a AWS S3 bucket.<br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/awslambda-toy-model)

## DevOps:
* #### CI Setting Up Workflow Jobs With Github Actions<br>
    This is a Python for DevOps repo, an example of CI using good practices. I have used a EC2 instance on cloud9 AWS environment, git and github actions to check the integrity of the code with a push as a trigger.<br>
Libraries used: (click, pytest, pylint, black, pytest-cov)<br>
[![](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/VM-137/aws-cloud9-devops)




