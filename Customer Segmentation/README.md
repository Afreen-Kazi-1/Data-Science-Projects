# Customer Segmentation Analysis
## Overview
This project focuses on customer segmentation using a dataset that includes various attributes such as income levels, product consumption, and family structure. The goal is to analyze customer spending patterns based on income levels and family size, providing insights that can inform targeted marketing strategies.

## Dataset
The dataset used in this analysis includes the following fields:

Income: The annual income of the customer.
Kidhome: The number of kids at home.
Teenhome: The number of teenagers at home.
MntMeatProducts: Amount spent on meat products.
MntFishProducts: Amount spent on fish products.
MntWines: Amount spent on wines.
MntSweetProducts: Amount spent on sweets.
MntFruits: Amount spent on fruits.
MntGoldProds: Amount spent on gold products.

## Objectives
The main objectives of this analysis are:

### - Data Filtering: 
To segment the customer base based on income levels and the presence of kids and teenagers at home.
Product Consumption Analysis: To calculate and visualize the total consumption of different product categories based on these segments.
### - Visualization: 
To create pie charts that represent the distribution of product consumption for customers with:
- Income less than 30k
- Income between 30k and 60k
- Income above 60k

## Methodology

### Data Preprocessing:

Filter the dataset to create subsets based on income levels.
Calculate the total spending for various product categories.

### K-Means Clustering
K-means clustering is an unsupervised algorithm that partitions data into K distinct clusters based on features. It starts by randomly initializing K centroids, then assigns each data point to the nearest centroid. Afterward, centroids are recalculated as the mean of assigned points. This process repeats until centroids stabilize. In customer segmentation, K-means groups customers by behavior or demographics, informing targeted marketing strategies and insights. However, selecting the right K and initialization can influence results.

### Data Visualization:
Generate pair charts using Seaborn for visulaizing clustering. 
Generate pie charts to visualize the percentage of product consumption for different income segments.

## Results
Upon running, the clustered customer csv file is generated that filters the data into clusters through K-Nearest Neighbors algorithms. 

## Conclusion
The insights derived from this customer segmentation analysis can assist businesses in crafting targeted marketing strategies based on customer spending habits. By understanding which products are favored by specific income segments, companies can enhance their product offerings and promotional campaigns.