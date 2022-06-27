#Overview
Customer segmentation analysis is an in-depth evaluation companies perform to better understand the value of their target audience groupings and to optimize their marketing efforts.

PROBLEM STATEMENT
A retail firm wants to understand their customers,and divide them into segments to optimize the significance of each customer to the business.

Objectives
Segment customers using a machine learning algorithm (KMeans Clustering) in Python.

Who are your target customers with whom you can start a marketing strategy?

PROCESSES

Understand the data

Drop features not needed for the clustering

Perform elbow method to find optimal number of clusters to be use for building the model

Training the model using unsupervised learning algorithm - KMeans to segment customers

Plotting the clusters

Understanding The Data
Import necessary libraries

Check shape and info of data

Check for missing values in data

Drop features not needed

Prepare data for clustering

Feature Engineering
Metrics that represent customers behaviour were created to from the already existing variables. The metrics includes Recency,Frequency and Monetary. Segmentation will be done using these metrics.

Data preprocessing for modelling
Here, the metrics are transformed using the square root function to enhace the KMeans clustering.

Perform Elbow Method to find the optimal number of clusters
KMeans form of clustering is used in this project were an iteration from 1-11 is clustered and plotted using a elbow plot

After the number of clusters to be used is determined.

Train the model
Initiate KMeans models with selected optimal number of clusters

Plot clusters to gain insight regarding our customers

Analyzing each cluster
Here, analysis of each cluster to regards Recency Frequency and Monetary value is provided.

Conclusion and Recommendations
This is the final stage. It comprises the report on the the findings from the project and recomendations.
