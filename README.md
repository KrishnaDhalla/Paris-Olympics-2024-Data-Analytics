# Paris Olympics 2024 Data Analytics

## Overview

This project showcases the implementation of an **end-to-end data engineering pipeline** using **Azure services**. The dataset used is sourced from **Kaggle**, covering data related to the **Paris Olympics 2024**. The project involves data ingestion, transformation, analysis, and visualization.

## Dataset

The dataset is publicly available on **Kaggle** and in this GitHub repository. It consists of the following CSV files:
- **Athletes**: Details of individual athletes.
- **Teams**: Information about participating teams.
- **Medals**: Medal data from the Paris 2024 Olympics.
- **Medallists**: Details of athletes who won medals.

## Project Workflow

### 1. Data Ingestion
- Data was ingested from my **GitHub repository** into **Azure Data Lake Storage (ADLS) Gen2**.
- Alternatively, **Azure Data Factory (ADF)** can be used to pull data directly from an API into ADLS.

### 2. Data Transformation and Cleaning
- **Azure Databricks** was used for data processing. 
- Data cleaning, transformation, and **exploratory data analysis (EDA)** were performed.
- The cleaned and transformed data was saved back to ADLS in a folder named **"Transformed Data"**.

### 3. Data Analysis
- **Azure Synapse Analytics** was used to run **SQL queries** on the transformed data to derive insights.

### 4. Data Visualization
- Basic **visualizations** were created using **Microsoft Power BI** to display key insights from the data.

## Queries Executed

Here are some of the key SQL queries and insights derived:

1. **Distribution of Medals by Gender**:
   - Analyzed how medals were distributed between different genders.

2. **Number of Medals by Sport**:
   - Counted the number of medals awarded in each sport category.

3. **Top 10 Countries with Maximum Medals**:
   - Identified the top 10 countries with the most medals.

4. **Count of Medals by Age**:
   - Calculated the age of each medalist at the time of winning and counted the medals won by different age groups.

5. **Countries Participated, Total Medals Earned, and Number of Sports Played**:
   - Compiled data on countries that participated, their total medal count, and the number of sports they participated in.

## Conclusion

This project demonstrates a comprehensive **data engineering pipeline** using **Azure services**, covering everything from **data ingestion** to **visualization**. It highlights the power of cloud-based tools for large-scale data processing and analytics.

---
  
### Tools Used:
- **Azure Data Factory**: For data ingestion.
- **Azure Data Lake Storage (Gen2)**: For storing raw and transformed data.
- **Azure Databricks**: For data transformation and cleaning.
- **Azure Synapse Analytics**: For running analytical queries.
- **Power BI**: For data visualization.

Feel free to explore the datasets and the SQL queries provided in the repository to gain more insights from the **Paris 2024 Olympics** data.
