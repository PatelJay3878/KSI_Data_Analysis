
# Toronto Police Accident Data Analysis




## Overview

This project focuses on analyzing traffic collision data from the Toronto Police Service, specifically focusing on accidents resulting in fatalities or serious injuries (KSI) over the past 10 years. The dataset provides insights into various aspects of traffic collisions, including contributing factors, locations, victim demographics, and temporal patterns. Python programming is used for data analysis, visualization, and modeling techniques such as clustering.
## Dataset
The dataset used in this project is the "Traffic Collisions - Killed or Seriously Injured (KSI) Data" provided by the Toronto Police Service and the City of Toronto. It contains information on persons killed or seriously injured in traffic collisions since 2006.
## Key Steps
1.	**Importing Necessary Libraries:** We start by importing essential Python libraries required for data analysis and visualization.
2.	**Importing Dataset:** The dataset containing Toronto police accident data for the past 10 years is imported for analysis.
3.	**Checking Missing Values:** We examine the dataset for missing values to ensure data quality and completeness.
4.	**Visualizing Missing Values:** Features with the highest missing values are visualized to identify patterns and inform data cleaning strategies.
5.	**Data Cleaning:** Columns with high missing values are dropped to prepare the dataset for analysis.
6.	**Exploring Data Relationships:** Various data relationships are explored to uncover patterns and insights into accident occurrences.
7.	**Heatmap Visualization:** A heatmap is created to visualize where fatalities have occurred in Toronto, providing spatial insights.
8.	![HeatMap](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/5f32848d-cb0a-472a-8767-6c7c21914e1d)
9.	**Accident Occurrence Patterns:** Patterns of accident occurrences with respect to different regions in Toronto are identified and analyzed.
10.	**Driving Conditions and Causes:** Types of driving conditions and causes responsible for accidents are examined to understand contributing factors.
11.	**Vehicle and Victim Types:** Types of vehicles and victims involved in accidents, as well as the outcomes of accidents on victims, are analyzed.
12.	**Accident Trends Over Time:** The number of accidents occurring each month and year is analyzed to identify trends and seasonal variations.



## Data Modeling
**Clustering Analysis using K-Means Algorithm**

•	**Identification of Important Features:** Features overlapping, containing missing values, or unrelated to the study are identified and removed.
•	**Creation of Dummy Variables:** Dummy variables are created for all categorical values to prepare the data for clustering.
•	**Determination of Number of Clusters:** The **Elbow Method** is employed to determine the optimal number of clusters.
•	**Cluster Analysis:** K-Means clustering is performed to segregate groups with similar traits and identify clusters.
•	**Insights from Cluster Analysis:** Insights are derived from the clustering results to understand accident patterns and hotspots in Toronto.

## Conclusion
Through comprehensive data analysis and modeling, this project sheds light on the patterns, trends, and contributing factors of accidents reported by the Toronto Police Service. By leveraging Python programming and advanced analytics techniques, this project aims to provide actionable insights for accident prevention and improving road safety in Toronto.
