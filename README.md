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
  [Your notebook answer to "What is the best value for k?" goes here.]

- PCA Explained Variance:
  The total explained variance for the three principal components was found to be [insert total variance here].

- Comparison & Analysis:
  [Your discussion regarding the differences (or similarities) in cluster results using the full features versus the PCA-reduced data.]

Disclaimer
-------
This project is my own code, Microsoft Copilot and Github Copilot were used to debug, suggest edits when stuck and review as necessary. 