# Data Engineering YouTube Trend Analysis

## Overview
This project focuses on securely handling, organizing, and analyzing YouTube video data, including both structured and semi-structured formats. The analysis will be based on video categories and trending metrics to gain valuable insights.

## Objectives of the Project

1. Data Ingestion: Develop a system to gather data from various sources.
2. ETL System: Convert the raw data into a usable format through extraction, transformation, and loading processes.
3. Data Lake: Establish a centralized repository to store data from multiple sources.
4. Scalability: Ensure the system can handle increasing data volumes as our data grows.
5. Cloud: Utilize AWS for processing large datasets, as local computers are insufficient.
6. Reporting: Create a dashboard to provide insights and answers to specific questions.

## Services Used

1. AWS IAM: AWS Identity and Access Management (IAM) is a crucial service that allows for secure management of access to AWS resources and services, enabling fine-grained control over user permissions and policies to enhance security.
2. Amazon S3: Amazon S3 is a highly scalable object storage service designed to provide robust data availability, security, and performance, making it ideal for a variety of storage needs including backups, archives, and big data analytics.
3. AWS Glue: AWS Glue is a serverless data integration service that simplifies the process of discovering, preparing, and combining data for analytics, machine learning, and application development. It automatically generates ETL code to transform data and make it queryable.
4. AWS Lambda: AWS Lambda is a serverless compute service that enables developers to run code in response to events without needing to provision or manage servers, thereby facilitating scalable and cost-effective execution of code.
5. AWS Athena: Amazon Athena is an interactive query service for analyzing data directly in Amazon S3 using standard SQL. It eliminates the need for data loading processes and allows for quick and easy data analysis directly from S3, making it efficient for ad-hoc querying and analysis.
6. QuickSight: Amazon QuickSight is a powerful, scalable, and serverless business intelligence (BI) service that leverages machine learning to deliver insights. Built for the cloud, it allows users to easily create and share interactive dashboards and reports.
7. Amazon CloudWatch: Amazon CloudWatch is a monitoring and observability service that provides data and actionable insights for AWS, hybrid, and on-premises applications and infrastructure resources. It allows you to collect and track metrics, collect and monitor log files, set alarms, and automatically react to changes in your AWS resources, helping ensure the smooth operation of your applications and infrastructure.

## Dataset Used

This Kaggle dataset offers comprehensive statistics on daily popular YouTube videos over several months, provided in CSV format. Each day, it tracks up to 200 trending videos from various regions, with each region's data stored in a separate file. The dataset includes details like video titles, channel names, publication times, tags, view counts, likes, dislikes, descriptions, and comment counts. Additionally, there is a category_id field, specific to each region, found in the associated JSON file.

You can explore the dataset here: https://www.kaggle.com/datasets/datasnaek/youtube-new.

## Architecture

![architecture](https://github.com/jeyakrishna/YouTube-Trend-Analysis/assets/29234907/6ea0109c-2cbf-409a-98e8-b369cbe72e22)




