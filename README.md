# Uber Data Analytics | Modern GCP Project

## Introduction 

1.Data Ingestion
Use Mage.ai to create an ETL (Extract, Transform, Load) pipeline. Import raw Uber trip data into Mage pipelines for preprocessing.

Store the raw data in Google Cloud Storage for scalability and easy access.

2. Data Transformation
Leverage Mage.ai for data cleaning and transformation. Create fact and dimension tables to structure your data effectively.

Use Python or SQL within Mage to handle tasks like converting timestamps, calculating trip durations, or categorizing data.

3. Data Warehousing
Load the transformed data into BigQuery. This will serve as your data warehouse, enabling large-scale data analysis.

Use BigQuery's SQL capabilities to run queries and generate insights, such as identifying peak hours, popular routes, or average trip durations.

4. Data Visualization
Connect BigQuery to Looker Studio to create interactive dashboards.

Design visualizations like heatmaps for trip density, bar charts for revenue trends, or line graphs for trip counts over time.

5. Optimization and Scalability
Use BigQuery's streaming capabilities for real-time data ingestion if needed.

Optimize your Cloud Storage buckets with lifecycle management to reduce costs by transitioning older data to colder storage classes.

6. Insights and Reporting
Use Looker Studio to generate reports that highlight key metrics, such as driver performance, customer satisfaction trends, or operational efficiency.

## Architecture 
