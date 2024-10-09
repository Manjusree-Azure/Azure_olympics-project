# Azure_olympics-data engineering project

The Olympic Data Engineering Project aims to build a scalable and efficient data pipeline that collects, processes, and analyzes Olympic Games data. The main objectives include:

![Architecture](https://github.com/Manjusree-Azure/Azure_olympics-project/blob/main/Tokyo%20Olympics%20Architecture.png)

# Data collection

Data Collection: Ingesting CSV files from My Github(Source dataset from Kaggele) repository to Azure datalake Gen2 and ingested the data using Azure data factory.
![Resurce setup](https://github.com/Manjusree-Azure/Azure_olympics-project/blob/main/Resource%20setup_olympic.png)

AZURE DATA LAKE GEN2

![ADLGen2](https://github.com/Manjusree-Azure/Azure_olympics-project/blob/main/ADLGen2%20data_Olympic.png)

AURE DATA FACTORY PIPELINE

![ADF](https://github.com/Manjusree-Azure/Azure_olympics-project/blob/main/ADF%20pipeline_olympic.png)


# Data Tranformation:

Data Transformation: Cleaning, transforming, and organizing the raw data into structured formats, making it ready for analysis using Databricks and store the curated data in Azure dadalake gen2.

![Databricks](https://github.com/Manjusree-Azure/Azure_olympics-project/blob/main/olympic%20data%20transformation.ipynb)


# Data Storage:
Data Storage: Utilizing scalable storage solutions Azure Data Lake gen2 to store both raw and processed data.

# Data Analysis:
Data Analytics: Implementing analytics and reporting to generate insights, such as medal predictions, athlete performance trends, and country-wise statistics using Azure synapse analytics, here i used SQL for data querying and analysis.

![Azure Synapse Analytics](https://github.com/Manjusree-Azure/Azure_olympics-project/blob/main/synapse_analytics_report.png)


# optimization
Optimization: Ensuring the system handles large volumes of data efficiently and is capable of real-time data processing during live events using powerBI or Tableu.

# Goal of this project:
It offers me handson experience about real time projects.
Analyze athlete performance trends over time.
Track medal counts and rankings for each Olympic event.
Predict future trends in Olympic sports using historical data.
Provide data-driven reports and insights for stakeholders (e.g., Olympic committees, sponsors).


