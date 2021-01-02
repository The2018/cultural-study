# Cultural study

This project is dedicated to the application of machine learning algorithms and tools to analysis of anthropological and sociological datasets. We would experiment with both supervised and unsupervised learning algorithms, such as clustering, decision trees, association rules, and artificial neural networks and many others. The goal is to extract meaningful patterns from such datasets as World Value Survey.

## Data Cleaning: 

Before we apply any algorithms to the WVS data, we need to make sure that the data has high quality. We need to detect and correct corrupt, invalid, or inaccurate records from the data set and changing the range of data value for easiler processing later.

## Clustering & Evaluation:

We cluster the cleaned data using kmeans. We try to find the best k using elbow point and evalute our clustering result by confusion matrix. We also visualize the culture cluster with google map, as in 01.html.

## PCA & Feature Selection:

We apply PCA to cleaned data and select the features with highest loading scores to do clustering again. We also checked that people in the same country assimilate more to each other than people from other countries. After applying feature selections, this result improved compared with using all features.
