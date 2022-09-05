# Credit-Card-Dataset-for-Clustering
Credit Card Customer Clustering (Unsupervised learning) project as a part of my training With SHAI For AI | شاي للذكاء الاصطناعي (Shai training 2022)  


Clustering is an unsupervised technique of grouping objects together based on their properties. By doing so, the objects in one group are more similar to each other than to those in other groups.

This task requires to develop a customer segmentation to define marketing strategy. The
sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

Following are the features for Credit Card dataset:

- **CUSTID** : Identification of Credit Card holder (Categorical)
- **BALANCE** : Balance amount left in their account to make purchases (
- **BALANCEFREQUENCY** : How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
- **PURCHASES** : Amount of purchases made from account
- **ONEOFFPURCHASES** : Maximum purchase amount done in one-go
- **INSTALLMENTSPURCHASES** : Amount of purchase done in installment
- **CASHADVANCE** : Cash in advance given by the user
- **PURCHASESFREQUENCY** : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
- **ONEOFFPURCHASESFREQUENCY** : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
- **PURCHASESINSTALLMENTSFREQUENCY** : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
- **CASHADVANCEFREQUENCY** : How frequently the cash in advance being paid
- **CASHADVANCETRX** : Number of Transactions made with "Cash in Advanced"
- **PURCHASESTRX** : Number of purchase transactions made
- **CREDITLIMIT** : Limit of Credit Card for user
- **PAYMENTS** : Amount of Payment done by user
- **INIMUM_PAYMENTS** : Minimum amount of payments made by user
- **PRCFULLPAYMENT** : Percent of full payment paid by user
- **TENURE** : Tenure of credit card service for user

I visualized the data by use many technical, one of them was autoviz which have many plots for data, after that I found some missing values and outliers. So, I preprocessed them and did scaling to prepare them to try some ML clustering algorithms.
I used Elbow and silhouette to choose optimal number of clusters which was 4.
I used Affinity Propagation, Agglomerative, BIRCH, DBSCAN, K-means, Mini-Batch K-Means, OPTICS, SpectralClustering.
The best result I got was from K-means clustering and Mini-Batch K-Means clustering.
And I used PCA to reduce the dimensions of the data and plot, also I used pycaret library 
For 3d result plotting.
![Elbow](https://user-images.githubusercontent.com/96171965/188399766-a1a269c4-4294-41ef-bae6-61b6f4ac26dc.png) ![silhouette ](https://user-images.githubusercontent.com/96171965/188399914-74f9e5a4-cf84-4d44-a6d0-85fbba050fd2.png)
![CreditCard](https://user-images.githubusercontent.com/96171965/188399937-e010daa6-d0d2-4a00-a43c-fd966307e4c2.png)

