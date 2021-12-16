# Cryptocurrencies

The deliverables for this Challenge were:

## Preprocessing the Data for PCA
*  data cleaned to include only those crypto traded, the istrading column removed, columns with null values removed, data that do not have coins being mined removed, the column CoinName is dropped
*  a new DataFrame is created to store the CoinName
*  Get_dummies method is performed and a new DataFrame X is created
*  the X dataframe is standardized using StandardScaler fit_transform function

## Reducing Data Dimension Using PCA
* The PCA algorithm reduces the dimensions of the DataFrame down to 3 principal components
* The pcs DataFrame is created and houses the 3 principal components adn had the index from the original DataFrame

## Clustering Cryptocurriences Using K-means
* The KMeans algorithm is used to cluster the cryptocurriences using the PCA data where the following steps have been completed:
  * an elbow curve
  * predictions made on the K clusters of cryptocurrencies
  * A new DataFrame is created

## Visualizing Cryptocurrencies Results
* The clusters are plotted using a 3D scatter plot
* A table with tradable cryptocurriences is created using hvplot.table()
* The total number of tradable cryptocurrencies is printed
* A DataFrame is created
* A hvplot scatter plot is created showing the clusters or classes of data
