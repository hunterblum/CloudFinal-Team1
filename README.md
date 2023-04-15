# MSADS508: Data Science Cloud Computing - Final Project
## Torrero Agronomy: Creating an Worldwide Agricultural Ranking System for Individual Producers

## Completed 06/16/2023

### Installation

To use this project, first clone the repo on your device using the commands below:

`git init`

`git clone https://github.com/hunterblum/CloudFinal-Team1.git`

### Partner(s)/Contriubutor(s)
* [Hunter Blum](https://github.com/hunterblum)
* [Jacqueline Urenda](https://github.com/jackieure)
* [Ebad Akhter](https://github.com/ebadakhter)

**Company Name:** Torrero Agronomy

**Company Industry:** Agronomy/ Agriculture/ Agribusiness

**Company Size:** 3 (startup)

### Methods
* Data Exploration
* Pre-processing
* Data Visualization
* Statistical modeling

### Technologies
* Python (AWS Sagemaker)
* SQL Transformations
* AWS (Sagemaker, Athena, S3)

### Abstract
Torrero Agronomy specializes in agronomic consultation and provides commodity recommendations to producers of crops and livestock. The company is expanding to worldwide consultation and wants a model to provide automated commodity recommendations to our customers.

### Problem Statement
Since 1960, global food production has been substantially increasing to keep up with the food demand caused by population increases. As the agriculture industry is challenged with meeting these high demands, many farmers and ranchers are seeking ways to efficiently optimize its resources and increase their sales. There are various factors that can affect food production such as rain, temperature, fertilizers, etc. It is important to understand how these challenges can affect land and its produce outputs (OECD, 2023). Our agronomy company, Torrero Agronomy, was tasked with creating a recommender model that will provide agricultural producers the top commodities that they should produce based on the total value (USD).

### Goals
1. Create a commodity recommendation system that gives producers the most valuable commodities based on location, weather, and fertilizer practices.
2. Explore how weather, agricultural practices, and production vary across the world. 
3. Compare traditional and Amazon Web Services (AWS) models to evaluate the AWS’s value to the company.


### Non-Goals 
Our focus is to provide sound data analytics and practical solutions to our clients, without attempting to predict individual yields or profits, recommend changes to agricultural practices, or incorporate complex currency exchanges or trade relationships between countries.


### Data Sources
The data will be stored in an S3 Bucket on the AWS service and will be communicated with AWS Sagemaker. There will be 5 files in total, uploaded to the AWS S3 Bucket and combined into a `df_merged.csv` file for Athena SQL Database.

  * FAO sourced datasets:
https://www.fao.org/faostat/en/#data

* World Bank / Kaggle sourced datasets:
https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset


### References
Food and Agriculture Organization of the United Nations (FAO). (2012). Sustainability and Organic Livestock. Sustainability Pathways: Sustainability and organic livestock. Retrieved March 13, 2023, from https://www.fao.org/nr/sustainability/sustainability-and-livestock
Organization for Economic Co-operation and development (OECD). (2023). How we feed the world today. OECD. Retrieved April 1, 2023, from https://www.oecd.org/agriculture/understanding-the-global-food-system/how-we-feed-the-world-today/ 


## Presentations and projects  
* [Amazon SageMaker (AWS) Python - Jupyter Notebook](https://github.com/hunterblum/CloudFinal-Team1/blob/main/Cloud_Team1.ipynb)
