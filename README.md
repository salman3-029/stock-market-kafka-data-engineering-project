# Stock Market Kafka Real Time Data Engineering Project

## Introduction 
In this project, you will execute an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.

We are going to use different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

## Customisation
This project was executed from local machine using Docker Jupyter image available at: https://hub.docker.com/r/jupyter/scipy-notebook
This container did not allow for sudo rights, hence I could not install AWS CLI which was needed to upload data to S3 from Kafka Consumer.
However, I have used `boto3` library as an alternative. 
## Architecture 
<img src="Architecture.jpg">

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka


## Dataset Used
You can use any dataset, we are mainly interested in operation side of Data Engineering (building data pipeline) 

Here is the dataset used in the video - https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv


## Complete Video Tutorial 

Video Link - https://www.youtube.com/embed/KerNf0NANMo
