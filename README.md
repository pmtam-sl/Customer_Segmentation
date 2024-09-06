# Customer Segmentation Project

## Overview

This project applies machine learning techniques to perform customer segmentation, helping the marketing team at a bank identify distinct customer groups based on transaction frequency, transaction amounts, tenure, and other relevant features. The goal is to enable more targeted marketing strategies and campaigns.

## Dataset

The dataset contains anonymized customer records over the past six months. Refer to the project document for detailed data descriptions.

## Methodology

1. **Exploratory Data Analysis (EDA)**: Understand the data distribution and identify patterns.
2. **Data Preprocessing**: Clean the data to remove any inconsistencies or missing values.
3. **Feature Scaling**: Standardize the features to ensure they are on the same scale before clustering.
4. **Model Training**:
    - Apply **K-Means clustering** to segment customers.
    - Use the **Elbow method** to determine the optimal number of clusters.
    - Visualize the clusters using **Principal Component Analysis (PCA)**.
5. **Model Evaluation and Conclusion**:
    - Evaluate the clustering result using the **Silhouette score**.

## Results

The analysis identified four significant customer clusters:

- **Cluster 1:** High Spending, High Balance
- **Cluster 2:** High Balance, Low Spending
- **Cluster 3:** Low Balance, High Cash Advance
- **Cluster 4:** Low Balance, Low Spending

*Final report in Quarto Pub can be viewed [here](https://pmtam.quarto.pub/customer-segmentation-with-python/)*

