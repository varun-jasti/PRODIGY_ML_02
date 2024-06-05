# K-means Clustering Algorithm

## Dataset used : [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

To create a K-means clustering algorithm for grouping customers of a retail store based on their purchase history, we will follow these steps:

## 1.Load the dataset.
First, we load the dataset using pandas, which lets us read data from a CSV file into a DataFrame. We also display the first few rows to understand what the data looks like.

## 2.Explore and preprocess the data.
We then explore the dataset to check for any missing values and get a basic understanding of it. We select important features like 'Annual Income' and 'Spending Score' for our clustering task.

## 3 Determine the optimal number of clusters using the elbow method.
To find out the best number of clusters, we use the elbow method. This involves plotting the within-cluster sum of squares (WCSS) for different numbers of clusters and looking for the point where the decrease in WCSS slows down.

## 4.Apply the K-means algorithm.
Next, we apply the K-means clustering algorithm to the dataset with the optimal number of clusters identified in the previous step. Each customer is assigned to a cluster, and this information is added to the DataFrame.

## 5.Visualize the clusters.
Finally, we visualize the clusters by plotting the data points for 'Annual Income' and 'Spending Score', with different colors for each cluster. We also plot the centroids of each cluster to show the center points of the groups.