# Cryptocurrencies Analysis using Unsupervised Learning
This Project comprises of four technical analysis to determine popular cryptocurrencies in the trading market and understand the grouping to create classifications. We used Unsupervised machine learning to group the cryptocurrencie and clustering algorithm was usedto determine the efficiency.

* 1: Preprocessing the Data for PCA
* 2: Reducing Data Dimensions Using PCA
* 3: Clustering Cryptocurrencies Using K-means
* 4: Visualizing Cryptocurrencies Result
## 1. Preprocessing the Data for PCA
In this step we performed data cleaning wherein we removed null values and cryptocurrencies without coins mined. Also, we used the encoding method "get_dummies()" for the text features and StandardScaler() to standardize and transform the data.
## 2. Reducing Data Dimensions Using PCA
In this step, we reduced dataframe's dimensions to three principal components and created a new dataframe.
## 3. Clustering Cryptocurrencies Using K-means
We created an elbow curve to find the best value for the clustering groups and a used  K-means algorithm to predict the K clusters for the cryptocurrencies’ data.
## 4. Visualizing Cryptocurrencies Result
Finally, we created: 
* Elbow curve using hvplot
* 3D scatter plot to visualize the three PCAs
* 2D scatter plot to visualize "Total Coins Mined" vs. "Total Coin Supply" by coin name and clusters
 
### Elbow curve to determine the cluster count
![alt text](https://github.com/nikmahadeshwar/Cryptocurrencies/blob/main/elbow_curve.png)
### 3D scatter plot to visualize the three PCAs
![alt text](https://github.com/nikmahadeshwar/Cryptocurrencies/blob/main/3Dplot.png)
### 2D scatter plot to visualize "Total Coins Mined" vs. "Total Coin Supply" by coin name and clusters
![alt text](https://github.com/nikmahadeshwar/Cryptocurrencies/blob/main/2dplot.png)
