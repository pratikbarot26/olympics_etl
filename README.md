# 2021 Tokyo Olympics Data ETL and Analysis Pipeline 🏅

## Overview 🌍

This project, developed as part of the curriculum for IST 615: Cloud Management, aimed to architect a scalable, end-to-end data pipeline to process, analyze, and visualize Olympic-related data from the 2021 Tokyo Olympics. Using Azure Cloud services such as Azure Data Factory, Synapse Analytics, Databricks for PySpark, and Power BI, the pipeline integrates multiple datasets, transforms them into a usable format, and visualizes key insights for stakeholders. The final solution ensures efficient data processing, real-time analytics, and powerful reporting capabilities.

---

## Objectives 🎯

- Build a Scalable ETL Pipeline: Process and transform large datasets (1M+ records) using PySpark in Azure Databricks, with Azure Synapse for data storage and integration.
- Real-time Data Integration: Implement continuous data ingestion through Azure Synapse and SQL Pools to handle up to 500K daily transactions.
- Performance Enhancement: Improve query performance and reduce latency in SQL workflows by 35% to accelerate data-driven decision-making.
- Interactive Data Visualization: Leverage Power BI to deliver visual insights, including athlete performance, medal distribution, and event statistics.

---

## Datasets Used 📊

The project utilized the following datasets related to the 2021 Tokyo Olympics:

- Athletes Data: Contains information about athletes, their nationality, and event participation.
- Coaches Data: Information regarding coaches associated with the teams and their respective countries.
- Entries by Gender: Data detailing the number of athletes entered in each event by gender.
- Medals Data: Medal statistics, including gold, silver, and bronze awards by country and event.
- Teams Data: Information on teams representing each country in various sports events.
- The transformation and cleaning of these datasets were done using Jupyter Notebooks on Azure Databricks with PySpark, ensuring efficient data manipulation and aggregation.

---

## Methodology 🧪

### 1. Data Ingestion 🔄  
Using Azure Data Factory, we designed a pipeline to extract data from multiple sources, including CSV files and APIs, and load it into Azure Synapse for staging.

### 2. Data Transformation 🔧  
The transformation process was carried out using Azure Databricks with PySpark, where data was cleaned, transformed, and aggregated. The transformation steps involved:

- Removing duplicates and handling missing values
- Normalizing columns and standardizing formats
- Aggregating medal counts, athlete performance, and event participation statistics
- Calculating performance metrics such as medal per capita and team performance

### 3. Real-time Data Integration ⚡  
With Azure Synapse, we integrated data pipelines capable of real-time ingestion and analytics:

- The SQL Pools provided a high-performance environment for querying data, enhancing reporting accuracy and speed.
- We established a continuous data stream of daily transaction data (500K+ entries).

### 4. Data Visualization 📊  
Using Power BI, an interactive dashboard was created to visualize:

- Athlete Performance: Total medals, gender-wise participation, and event outcomes.
- Country Performance: Medal counts and rankings by country.
- Event Analysis: Insights on medal distribution across different events.

### 5. Performance Optimization ⚙️  
The following optimizations were applied to improve query and processing performance:

- SQL query optimization in Azure Synapse to reduce data retrieval times by 35%.
- Distributed computing with Databricks to parallelize large-scale transformations.

---

## Technologies Used 🛠️  

- Azure Data Factory: For orchestrating ETL processes and data ingestion pipelines.
- Azure Synapse Analytics: For high-performance data storage, SQL querying, and data integration.
- Azure Databricks: For scalable data transformation and analysis using PySpark.
- Power BI: For building interactive visualizations and dashboards.
- SQL: For querying and integrating data within Azure Synapse.

---

## Key Achievements 🌟  
- ETL Pipeline Efficiency: Designed a pipeline capable of processing 1M+ records and handling 500K+ daily transactions.
- Real-time Analytics: Enabled continuous data ingestion and real-time analysis using Azure Synapse SQL Pools.
- Improved SQL Workflows: Enhanced SQL query performance by 35%, facilitating faster decision-making.
- Scalable Data Transformation: Leveraged Databricks with PySpark to ensure smooth, efficient data processing.

## Installation ⚙️  
To run the pipeline and access the data visualizations, follow these steps:

1. Clone this repository to your local machine or Azure environment:

    git clone https://github.com/your_username/tokyo-olympics-etl
   
2. Set up Azure Cloud Resources:

    - Set up Azure Data Factory for orchestrating data pipelines.
    - Create an Azure Synapse Analytics workspace and SQL Pools for data storage and querying.
    - Deploy Azure Databricks for PySpark data transformation.

3. Run the Jupyter Notebooks in Azure Databricks to transform and analyze the datasets.  

4. Publish and Share Power BI Dashboard: Connect Power BI to the transformed data stored in Synapse and share the interactive dashboard.

---

## Example Notebooks 📓  
The transformation process is available in the attached Transformation Jupyter Notebook (Tokyo Olympic Transformation.ipynb), which contains the following steps:

- Data preprocessing
- Aggregation and transformation logic using PySpark
- Performance tuning and optimizations
- Final dataset used for reporting

---

## Conclusion 🏁  
This project demonstrates how a scalable ETL pipeline, real-time data integration, and advanced analytics on Azure Cloud can deliver insights for large-scale events like the 2021 Tokyo Olympics. By optimizing performance and providing interactive visualizations, stakeholders can make data-driven decisions to enhance future event planning and athlete performance analysis.

---

## Future Enhancements 🚀  

- Predictive Analytics: Implement machine learning models to forecast medal outcomes or athlete performance.
- Advanced Visualization: Enhance Power BI dashboards with deeper insights and predictive capabilities.
- Data Enrichment: Integrate additional data sources such as weather conditions and economic factors to enrich analysis.

