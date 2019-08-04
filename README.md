# Customer-Segmentation

1-Importing and Exploring the data 

-Importing libraries

-Missing values

-Dropping null values

-Duplicate rows

-Number of unique values for each feature

-Customers from each country

--Correcting some coutry names

-Number of invoices per country

-Total revenue per country

-Negetive quantities

--cancelled invoices

-Time features

2-Recency-Monetary-Frequency (RMF) analysis

-Creating recency dataframe

-Creating monetary dataframe

-Creating frequency dataframe

-Creating RFM dataframe

3-Creating product categories

-Keywords occurances in the product descriptions

-Product description word cloud

-Creating keyword feaures

-Clustering description keywords

--SVD

--PCA

-KMeans clustering of description keywords

--TSNE visualization of keyword clusters

4-Categorizing customers based on RMF and products purchased

-Intermediate datasets

-Final customer ID dataset consisting of RMF features and product category features

-Clustering customer ID dataset

--Removing outliers for better clustering

--Clustering after outlier removal

--TSNE visualization of customer clusters

-Visualizing customer clusters

-Classification algorithms to predict new customer cluster

--Splitting data into training and test sets

--Logistic regression

--SGD

--SVC

--Random Forest

--Stacking classifiers
