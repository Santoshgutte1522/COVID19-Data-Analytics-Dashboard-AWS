# COVID19-Data-Analytics-Dashboard-AWS
End-to-end AWS Cloud Data Analytics project using Amazon S3, AWS Glue, Athena, and Power BI for COVID-19 data analysis and visualization.
# COVID-19 Data Analytics Dashboard using AWS and Power BI

## Overview

This project presents an end-to-end cloud-based data analytics solution for analyzing and visualizing COVID-19 data. The architecture leverages AWS services for data storage, metadata management, and serverless querying, while Microsoft Power BI is used to build interactive dashboards for generating business insights.

The project demonstrates the implementation of a scalable and serverless analytics pipeline capable of transforming raw data into meaningful visualizations and supporting data-driven decision-making.

---

## Architecture

```
COVID-19 Dataset
        │
        ▼
Amazon S3
        │
        ▼
AWS Glue Database
        │
        ▼
AWS Glue Crawler
        │
        ▼
AWS Glue Data Catalog
        │
        ▼
Amazon Athena
        │
        ▼
SQL Analysis
        │
        ▼
Microsoft Power BI
        │
        ▼
Interactive Dashboard
```

---

## Technology Stack

* Amazon S3
* AWS Glue
* AWS Glue Crawler
* AWS Glue Data Catalog
* Amazon Athena
* Microsoft Power BI
* SQL

---

## Project Objectives

* Build a serverless cloud analytics pipeline using AWS.
* Store and manage structured data using Amazon S3.
* Automatically catalog metadata using AWS Glue.
* Perform SQL-based analysis with Amazon Athena.
* Develop interactive visualizations and dashboards using Power BI.
* Generate meaningful insights from COVID-19 data.

---

## Data Processing Workflow

### Data Ingestion

COVID-19 data is stored in Amazon S3.

### Metadata Discovery

AWS Glue Crawler scans the dataset and creates metadata tables in the Glue Data Catalog.

### Query Processing

Amazon Athena is used to perform serverless SQL analysis on the dataset.

### Data Visualization

Microsoft Power BI is used to create interactive dashboards and visualize key metrics and trends.

---

## SQL Analysis

The following analyses were performed:

* Displaying sample records from the dataset.
* Top 10 countries by confirmed cases.
* Top 10 countries by deaths.
* Top 10 countries by recoveries.
* Global COVID-19 statistics.
* Daily trend analysis.

---

## Dashboard Components

### Key Performance Indicators

* Total Confirmed Cases
* Total Deaths
* Total Recovered Cases
* Active Cases
* Recovery Rate

### Visualizations

* Top 10 Countries by Confirmed Cases
* Top 10 Countries by Deaths
* Top 10 Countries by Recoveries
* Confirmed Cases Trend Over Time
* Recovery Trend Analysis
* Death vs Recovery Comparison
* Country-wise Geographical Analysis

### Interactive Filters

* Date Slicer
* Country Slicer

---

## Repository Structure

```
COVID19-Data-Analytics-Dashboard-AWS
│
├── README.md
├── COVID19_Data_Analytics_Dashboard_Report.pdf
├── Architecture_Diagram.png
├── screenshots
├── SQL_Queries.sql
└── powerbi_dashboard.pbix
```

---

## Key Learnings

* Cloud Storage using Amazon S3
* Metadata Management with AWS Glue
* Serverless Query Execution with Amazon Athena
* SQL-Based Data Analysis
* Business Intelligence and Dashboard Development using Power BI
* End-to-End Cloud Data Analytics Pipeline

---

## Future Enhancements

* Real-time data ingestion
* Automated pipeline orchestration
* Predictive analytics using machine learning models
* Integration with external APIs
* Scheduled dashboard refresh

---

## Author

Santosh Gutte

Computer Engineering Student

Vivekanand Education Society's Institute of Technology

Mumbai, India
