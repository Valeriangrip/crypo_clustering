# Crypto Clustering

# Description
This assignment is an inquiry towards crypto currencies and clustering with the KMeans library from sklearn, and plotting it accordingly in hvplot.
The crypto data csv file is loaded with initally about 1200 crypto's , but after data preprocessing to remove non trading, 0 coins mined, and nulls from the
data set about 533 crypto's are left for further analysis.
Dummies will be then made for the text features and then scaled and transformed
PCA Interpretation will then be used with 3 dimensions of the scaled data.
An elbow curve for the best K value is determined with the previous data.
The PCA Dataframe and crypto dataframe is then merged in order to proceed with a scatter 3d plot, with the 3 dimensions of PC1 PC2 and PC3
A tradeable table is then created with the hvplot.table function , and then a scatter 2d plot , with the dimensions of total coins mined vs total coin supply

Unit 13 AWS notebooks regarding KMeans will be utilized

Code Snippets

//
