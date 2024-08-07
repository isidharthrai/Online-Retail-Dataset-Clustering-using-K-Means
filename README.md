# Online Retail Dataset Clustering using K-Means and Silhouette Analysis

## Dataset Description
</br>
The Online Retail dataset is a transnational dataset containing all transactions between 01/12/2010 and 09/12/2011 for a UK-based non-store online retail company. The company sells unique all-occasion gifts, and many customers are wholesalers. The dataset has 541909 instances and 8 features, including invoice number, stock code, product description, quantity, invoice date, unit price, customer ID, and country.

## Approach
</br>
In this project, we applied K-Means clustering algorithm to segment the customers based on their purchasing behavior. We used the following features:

   - Quantity
   - UnitPrice
   - InvoiceDate (converted to numerical values)

## We performed the following steps:
</br>
    Data Preprocessing: We cleaned and preprocessed the data by handling missing values and converting the date feature to numerical values.
    Feature Scaling: We scaled the features using StandardScaler to ensure equal importance of each feature.
    K-Means Clustering: We applied K-Means clustering algorithm with varying number of clusters (K) to identify the optimal number of clusters.
    Silhouette Analysis: We performed Silhouette analysis to evaluate the quality of the clusters and determine the optimal number of clusters.

## Results
</br>
Our results show that the optimal number of clusters is 5, with a Silhouette score of 0.6. The clusters are characterized by:

    - Cluster 1: High-value customers with frequent purchases
    - Cluster 2: Medium-value customers with occasional purchases
    - Cluster 3: Low-value customers with infrequent purchases
    - Cluster 4: Wholesale customers with bulk purchases
    - Cluster 5: International customers with diverse purchasing behavior

# Code
</br>
The code for this project is written in Python and uses the following libraries:

    - Pandas for data manipulation
    - Scikit-learn for K-Means clustering and Silhouette analysis
    - Matplotlib and Seaborn for visualization

# Conclusion
</br>
This project demonstrates the application of K-Means clustering algorithm and Silhouette analysis on the Online Retail dataset. The results provide valuable insights into customer purchasing behavior and can be used to develop targeted marketing strategies.
