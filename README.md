# Customer Segmentation Analysis
<div class="row">
 <img src= "https://user-images.githubusercontent.com/77315991/233651077-126252dd-cb72-47f1-8d2a-84da1dd4e676.png" width= 250>
 <img src= "https://user-images.githubusercontent.com/77315991/233402040-307fa941-b6dd-4438-8cbd-e075c2f47151.png" width= 100>
<div>

A project submission to Nanyang Technological University for the course SC1015 (Introduction to Data Science & Artificial Intelligence).

Dataset is obtained from [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis), titled "Customer Personality Analysis".

## Problem Motivation
* Supermarkets attract a diverse range of customers with differing preferences and needs. Effective advertising required a tailored approach towards targeting the needs and wants of each customer.
* Our chosen problem statement: How can supermarkets leverage machine learning to identify customer segments based on customer attributes?
* With many different Clustering algorithms available, how can we identify the most optimal model that can segment the supermarket's customers?

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

## Clustering Algorithms Used
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
* K-Means Clustering yielded the best results overall
* Customers can be segmented into 4 clusters, eac with their own demographic traits: Income, Age, Number of Children, Education (specifically Third Cycle).
* These clusters have differing spending behaviours: Receptivity to Campaigns, Compain Tendencies, Highest Expenditure Product Categories and Prefered Purchase Avenue.
* More detailed conclusions can be found in the notebook.

<div class="row">
 <img src= "https://user-images.githubusercontent.com/77315991/233650044-d510901c-7e08-4443-a0d3-fceb117b8320.png" width= 500>
 <img src= "https://user-images.githubusercontent.com/77315991/233650071-feecfd37-26da-4428-933b-b2d9a37e3c20.png" width= 500>
<div>

## Contributors
1. [Ng Li Lin Evonne](https://github.com/evonneng05)
2. [Wong Yu Fei](https://github.com/Ranchu2000)

## References
* https://neptune.ai/blog/clustering-algorithms
* https://www.analyticsvidhya.com/blog/2019/08/comprehensive-guide-k-means-clustering/
* https://www.analyticsvidhya.com/blog/2019/10/gaussian-mixture-models-clustering/
* https://analyticsindiamag.com/a-tutorial-on-various-clustering-evaluation-metrics/
* https://www.geeksforgeeks.org/ml-mean-shift-clustering/
* https://www.mygreatlearning.com/blog/introduction-to-spectral-clustering/
* https://www.datanovia.com/en/lessons/agglomerative-hierarchical-clustering/
* https://scentellegher.github.io/machine-learning/2020/01/27/pca-loadings-sklearn.html
* https://www.mikulskibartosz.name/pca-how-to-choose-the-number-of-components/
* https://www.kaggle.com/code/karnikakapoor/customer-segmentation-clustering
* https://www.kaggle.com/code/sonalisingh1411/customer-personality-analysis-segmentation
* https://www.kaggle.com/code/gaganmaahi224/9-clustering-techniques-for-customer-segmentation#Exploratory-Data-Analysis
* https://towardsdatascience.com/how-to-select-the-best-number-of-principal-components-for-the-dataset-287e64b14c6d
* https://towardsdatascience.com/clustering-evaluation-strategies-98a4006fcfc
