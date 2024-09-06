# Customer Segmentation Project

## Overview

This project uses machine learning techniques to perform customer segmentation, helping marketing team at a bank identify distinct customer groups based on customer's transaction frequency, transaction amounts, tenure, and other relevant features. The goal is to enable more targeted marketing strategies and campaigns.

## Dataset

The dataset used in this project contains anonymized customer records over the past six months. Refer to data description in the project document.

## Methodology

1. Exploratory Data Analysis
2. Data Preprocessing: Clean data.
3. Feature Scalling: Standardize the features before clustering
4. Model Training: 
    - Apply K-Means clustering and determine the optimal number of clusters using Elbow method
    - Visualise cluster using PCA
5. Model Evaluation and Conclustion
    - Evaluate clustering result using silhouette score

## Results

Identified four significant clusters:

- **Cluster 1:** High Spending, High Balance.
- **Cluster 2:** High Balance, Low Spending.
- **Cluster 3:** Low Balance, High Cash Advance
- **Cluster 4:** Low Balance, Low Spending.



