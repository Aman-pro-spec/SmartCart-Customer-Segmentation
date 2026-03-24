# SmartCart Customer Segmentation 🛒

## Overview
This project applies unsupervised machine learning techniques to analyze customer data and segment them into distinct, actionable clusters. By understanding the varying behaviors, income levels, and purchasing habits of different customer groups, businesses can deploy more targeted and effective marketing strategies.

## Methodology
The clustering pipeline was built using Python and Scikit-Learn, utilizing the following techniques:
* **Data Preprocessing:** Cleaning and scaling the dataset to prepare for modeling.
* **Dimensionality Reduction:** Applying Principal Component Analysis (PCA) to reduce feature space and visualize clusters in 3D.
* **K-Means Clustering:** Utilizing the Elbow Method (via the `kneed` library) to determine the optimal number of clusters.
* **Hierarchical Clustering:** Implementing Agglomerative Clustering (Ward linkage) to validate and build robust customer segments.

## Files in this Repository
* `amanSmartCart.ipynb`: The main Jupyter Notebook containing the complete Python code for data exploration, PCA, and cluster generation.
* `smartcart_customers (2).csv`: The dataset containing customer demographics, spending history, and platform engagement metrics.
* `SmartCart Clustering System.pdf`: A comprehensive report detailing the business context, methodology, and final cluster characteristics.

## Key Insights
*(Note: You can update these bullet points based on the specific findings in your PDF report)*
* **Cluster 0:** Average income, moderate spenders.
* **Cluster 1:** High income, high engagement, frequent catalog and web purchases.
* **Cluster 2:** Lower income, budget-conscious shoppers.
* **Cluster 3:** High income, top-tier spenders with the longest customer tenure.

## Technologies Used
* Python 3.12
* Scikit-Learn
* Pandas & NumPy
* Matplotlib (3D plotting)
