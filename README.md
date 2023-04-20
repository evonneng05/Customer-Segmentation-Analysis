# Customer-Segmentation-Analysis

<img src= "https://user-images.githubusercontent.com/77315991/233402040-307fa941-b6dd-4438-8cbd-e075c2f47151.png" width= 75>

A project submission to Nanyang Technological University for the course SC1015 (Introduction to Data Science & Artificial Intelligence).

Dataset is obtained from [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis), titled "Customer Personality Analysis".

## Problem Motivation
* Supermarkets attract a diverse range of customers with differing preferences and needs. Effective advertising required a tailored approach towards targeting the needs and wants of each customer.
* Our chosen problem statement: How can supermarkets leverage machine learning to identify customer segments based on customer attributes.
* With many different Clustering algorithms available, we wanted to identify the most optimal model that can segment the supermarket's customers.

## Approach Taken
1. Exploratory Data Analysis was performed to identify required preprocessing steps.
2. Preprocessing was done to clean and prepare the dataset for the models. Steps such as the replacement of null values, removal of outliers, scaling and one hot encoding was performed.
3. Data Visualisation was used to understand subtle relationships and distributions within the dataset.
4. Dimensionality Reduction was achieved through Principal Component Analysis.
5. The optimal cluster number was identified using Elbow Method, Hierarchical Graph and Gap Statistic.
6. 6 Clustering Algorithms across 5 Clustering methods were employed on the dataset.
7. Evaluation was performed on these 6 Clustering Algorithms using Silhouette Score, Calinski Harabaz Index and Davies Bouldin Index.
8. Profiling of the identified clusters was performed based on their demographic and behavioural characteristics.
9. Recommendations for the supermarkets were drawn from the results.

## Clustering Algorithms Used:
Connectivity/ Hierarchical Clustering
 * Agglomerative Clustering Model
 
Centroid/ Partition Clustering
 * K-Means
 * Mean Shift
 
Distribution Model
 * Gaussian Mixture Model
 
Density Model
 * Ordering Points To Identify the Clustering Structure (OPTICS)
 
Graph-based Model
 * Spectral Clustering
 
## Conclusions
* Customers can be segmented into 4 clusters, eac with their own demographic traits: Income, Age, Number of Children, Education (specifically Third Cycle)
* These clusters have differing spending behaviours: Receptivity to Campaigns, Compain Tendencies, Highest Expenditure Product Categories and Prefered Purchase Avenue
* More details conclusions can be found in the notebook

## Contributors
1. [Ng Li Lin Evonne](https://github.com/evonneng05)
2. [Wong Yu Fei](https://github.com/Ranchu2000)

## References
