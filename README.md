# Data Warehouse Implementation & Analysis for US Accidents 

# Project Overview
This project aims to establish an ETL (Extract, Transform, Load) pipeline for importing data into Google BigQuery from CloudSQL and Google Cloud Storage. It involves analyzing a comprehensive dataset on US road accidents to derive key performance metrics, enhancing road safety strategies and decision-making.

# Dataset
Source: US Accidents dataset from Kaggle, covering road accidents across all 50 states in the United States from 2016 to 2021.

Size: 1.15 GB CSV file.

Features: 47 columns with approximately 900K records.

# Cloud Architecture
Utilization of Google Cloud Platform services, including CloudSQL for data preprocessing and Google Cloud Storage for data export.

Design and implementation of a data ingestion pipeline into Google BigQuery for analytical processing.

# ETL Pipeline
Extract:

Data preprocessed in CloudSQL is exported to Google Cloud Storage.

A pipeline is designed to ingest data into BigQuery, triggered by an ETL script stored in the bucket.

Transform:

Data transformation processes are applied to refine and structure the data for analytical purposes.

Load:

The transformed data is loaded into Google BigQuery, utilizing a star schema for optimized query performance.

# Key Performance Metrics

Analysis revealed that California had the highest number of road accidents, with approximately 795k incidents recorded between 2018 and 2021.

The year 2021 observed the highest annual accident count.

December 2021 saw the highest monthly accident frequency, with the 23rd marking the day with the most incidents, accounting for 10% of the month's total.

# Conclusion
This project demonstrates the power of cloud analytics and data warehousing in processing large-scale historical data. By analyzing US road accident data, we've gained valuable insights into accident trends and high-risk areas, aiding in the development of targeted safety measures.

# Usage

Clone the repository to your local environment.

Ensure you have access to Google Cloud Platform services.

Follow the ETL pipeline steps for data extraction, transformation, and loading into BigQuery.

Use the provided SQL queries in BigQuery to analyze the dataset and extract key performance metrics.

# Contact Information
For any inquiries or further discussion, please feel free to contact: Rithwik Maramraju(rithwik.maramraju@sjsu.edu)

