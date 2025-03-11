# CryptoClustering

## **Description**

This assignment provides visualization on whether we can use python /colab to use unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

---
## Requirements
The implementation requires uploading the crypto_market_data.csv file to your Google Drive to access all scripts. This project leverages several libraries including pandas for data manipulation, holoviews and hvplot for visualization, and scikit-learn components (KMeans, PCA, and StandardScaler) for machine learning operations.

The analysis employs two distinct unsupervised learning approaches: the first section implements KMeans clustering to identify natural groupings within the cryptocurrency market data, while the second section applies Principal Component Analysis (PCA) for dimensionality reduction and pattern recognition.

## How to Run
In the file option, open Crypto_Clustering_SunilWilliams.ipynb. Copy the required data files -crypto_market_data.csv to the file folder in google colab. Run each line in sequential order, ensuring that the line finishes processing before proceeding to the next step


## **Outcomes**
Based on the analysis of scatter plots, we can conclude that reducing dimensionality through PCA preserved the effectiveness of our clustering model. Despite using fewer features, we maintained the same number of clusters as the original KMeans implementation, with similar distribution of data points across clusters. This demonstrates that the essential patterns in the data were retained even after dimensional reduction.
