# Customer-Credit-Card-Behaviour-Clustering
This project, "Customer Credit Card Behavior Clustering," is part of my Hacktiv8 coursework on unsupervised learning. It serves as both a requirement for my Hacktiv8 studies and a component of my personal portfolio in Data Science. I created this project with a fictional background, made solely for the purpose of the project. You can find my other personal projects on [Richard Edgina Virgo](https://github.com/REV04).

#### -- Project Status: Finished

## Project Intro/Objective

The purpose of this project is to cluster customer credit card data retrieved from BigQuery using SQL queries. I will conduct Exploratory Data Analysis (EDA) to explore the data for clustering purposes. This analysis will be used to label and cluster data based on credit card consumer behavior and activity. These labels will aid in identifying patterns, which will then be utilized for making future predictions.

### Methods Used
- DQL
- PCA
- K-means
- Data Visualization
- Data Analysis

### Technologies

- SQL
- Python

## Project Description

The dataset used for creating this model is sourced from BigQuery. It contains information about credit card customers. I performed Exploratory Data Analysis (EDA) to understand the data. After EDA, I applied feature engineering to enhance clustering and used Principal Component Analysis (PCA) for dimensionality reduction. The Elbow Method and Silhouette Plot were used to determine the optimal number of clusters. I then trained the model using K-Means clustering and conducted post-clustering EDA to differentiate each cluster's behavior.

There are 3 clusters:
- Cluster 0: Consists of credit card customers with high purchase transactions, small cash advances, moderate remaining balances, and high credit limits.
- Cluster 1: Includes credit card customers with low purchase transactions, low cash advances, low remaining balances, and low credit limits.
- Cluster 2: Characterized by credit card customers with low purchase transactions, high cash advances, high remaining balances, and moderate credit limits.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Exploratory Data Analysis (EDA), Model Training, EDA analysis, and summary are being kept in Python/Customer-Credit-Card-Behaviour.ipynb
3. Model Inference is being kept in Python/Customer-Credit-Card-Behaviour-Inference.ipynb
4. Model like K-means.pkl, PCA.pkl, and model_scaler.pkl are being kept in Model folder.
4. Credit card behaviour is being kept in Data_Set/Credit_Card_Behaviour.csv

## Contact

- If you have any question or want to contribute with this project, feel free to ask me in [linkedln](https://www.linkedin.com/in/richard-edgina-virgo-a7435319b/).
