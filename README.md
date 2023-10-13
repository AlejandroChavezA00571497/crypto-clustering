# crypto-clustering
Module 19 Challenge for the Tec de Monterrey Data Analysis Bootcamp, Introduction to Unsupervised Learning

Jupyter Notebook file that takes data from a CSV and performs unsupervised machine learning processes on it, specifically KMeans algorithm clustering and Principal Component Analysis.

Crypto_Clustering.ipynb is the main file, it uses data related to cryptocurrency prices, spread among 7 different features and performs the following operations on it: 
- Preparing the data by scaling it with StandardScaler()
- Finding best value for K by creating an elbow curve
- Clustering with a KMeans algorithm
- Optimizing the original data with PCA
- Generating an elbow curve for the PCA optimized data
- Clustering the PCA optimized data
- Visualizing differences by doing composite plots

This file exists in the main directory, which also contains the README, as well as the Resources Directory, which has the crypto_market_data.csv file that is used as an starting point.

Contributions:
- Data Analysis Bootcamp Classes
- https://scikit-learn.org/stable/modules/clustering.html
- https://holoviz.org/tutorial/Composing_Plots.html
