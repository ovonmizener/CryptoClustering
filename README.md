CryptoClustering
================

Module 19 Challenge assignment. 

Project Description
-------------------
In this project, we use Python and unsupervised learning techniques to analyze cryptocurrency market data. The goal is to determine if cryptocurrencies are affected by short-term (24-hour) or medium-term (7-day) price changes. We accomplish this by:
- Scaling the market data using StandardScaler.
- Utilizing the elbow method to identify the optimal number of clusters (k) on the original scaled dataset.
- Clustering the cryptocurrencies with K-Means and visualizing the resulting groupings.
- Reducing the feature space using Principal Component Analysis (PCA) to extract three principal components and comparing the clustering with the full feature set.
- Creating composite plots to contrast the elbow curves and cluster visualizations across both methodologies.

File Structure
--------------
CryptoClustering/Crypto_Clustering.ipynb      
Resources/crypto_market_data.csv   
Resources/README.txt 


How to Run the Project
----------------------
1. Clone the repository

2. Open the Notebook

3. Execute the Notebook


Results & Observations
------------------------
- Optimal Clusters:
  We applied the cluster method to both original and PCA scaled data. Both indicated an elbow at k = 4. This indicated that in either scenario we should be clustering our crpyto data into four clusters to better understand the data. 

- PCA Explained Variance:
  When we applied PCA with n_components = 3, the explained variance ratios for the first three principal components were approximately 0.3727, 0.3249, and 0.1892. Summing these values gives a total explained variance of about 0.8868, or roughly 88.7%. This indicates that 88.7% of the variance in the full dataset is retained with these three components, allowing us to reduce the dimensionality while preserving most of the information.

- Comparison & Analysis:  
  As noted above both the original scaled data and the PCA-transformed data suggest an optimal k of 4. Clustering on the PCA data—despite using fewer features—yields similar groupings as the full-featured data. But we did find that the use of PCA helped remove some noise, improving  efficiency while still letting us observe the data. This is worth the trade off as only a small portion of the variance (~11.3%) is not accounted for.


Disclaimer
-------
This project is my own code, Microsoft Copilot and Github Copilot were used to debug, suggest edits when stuck and review as necessary. 