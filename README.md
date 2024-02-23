
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
7.	![accident_caused_in_months](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/bb3cbfa8-2b3e-4213-8f31-6b491d657ff6)
![Deaths_year](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/b26d4869-b4f2-40c6-a3d3-82f52e353513)
![fatal_vs_non_fatal](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/0f604455-a7a4-49d0-a61f-e05814d23cf8)

![vehicle_type_vs_accident](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/d1394734-2019-4590-a5ba-4396f92ad0a2)
![victims_in_accidents](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/11bc8510-9bbc-42fd-937a-55f9fbf273f1)

8.	**Heatmap Visualization:** A heatmap is created to visualize where fatalities have occurred in Toronto, providing spatial insights.
9.	![HeatMap](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/5f32848d-cb0a-472a-8767-6c7c21914e1d)
10.	**Accident Occurrence Patterns:** Patterns of accident occurrences with respect to different regions in Toronto are identified and analyzed.
11.	![Neighborhood_vs_Accident](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/ab8d9581-b806-4d65-89dc-fbc901fa17c2)
12.	![district_vs_Accident](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/1fba49b3-2645-4701-8f1b-21e01d97e376)

13.	**Driving Conditions and Causes:** Types of driving conditions and causes responsible for accidents are examined to understand contributing factors.
14.![driving_condition_vs_accident](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/61048ea7-0b35-4107-8c32-20b403d3e630)


15.	**Vehicle and Victim Types:** Types of vehicles and victims involved in accidents, as well as the outcomes of accidents on victims, are analyzed.
16.![victims_in_accidents](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/3ef86c3e-f0d6-4c56-bbe4-afacd554fd66)
![vehicle_type_vs_accident](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/ba7191d8-5290-49e7-b963-d9468b0392d6)
17.	**Accident Trends Over Time:** The number of accidents occurring each month and year is analyzed to identify trends and seasonal variations.
	![trend_type_of_vehicle_involved](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/c3868fb3-4c35-4717-a3b5-df782dbf8307)
![trend_of_causes_of_accident](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/8db00b53-ec3f-4c58-bbd2-ee2f28fc1c23)
![No of Accidents_occured_inrespective_to_month_ _year](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/9907e2e2-4aa0-4700-8eda-127622923dc1)


## Data Modeling
**Clustering Analysis using K-Means Algorithm**
![K-means_clustering_Hood_name_vs_speeding](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/f0a8d799-02bc-4ac5-b6c0-f78eefa14424)

•	**Identification of Important Features:** Features overlapping, containing missing values, or unrelated to the study are identified and removed.
![important_features](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/1c3bfaac-5590-498b-ace3-4e12a31d8f0b)

•	**Creation of Dummy Variables:** Dummy variables are created for all categorical values to prepare the data for clustering.
•	**Determination of Number of Clusters:** The **Elbow Method** is employed to determine the optimal number of clusters.
![Elbow_method](https://github.com/PatelJay3878/KSI_Data_Analysis/assets/73180853/b1b2e35c-8a79-42cd-a4dc-f850d1a8e936)

•	**Cluster Analysis:** K-Means clustering is performed to segregate groups with similar traits and identify clusters.
•	**Insights from Cluster Analysis:** Insights are derived from the clustering results to understand accident patterns and hotspots in Toronto.


## Conclusion
Through comprehensive data analysis and modeling, this project sheds light on the patterns, trends, and contributing factors of accidents reported by the Toronto Police Service. By leveraging Python programming and advanced analytics techniques, this project aims to provide actionable insights for accident prevention and improving road safety in Toronto.
