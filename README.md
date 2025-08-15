# Mall Customer Segmentation using K-Means Clustering

## Dataset

The dataset contains 200 customer records with the following features:
- CustomerID
- Gender
- Age
- Annual Income (in thousand dollars)
- Spending Score (1-100) representing customer spending behavior

## Steps taken

- Loaded and explored the dataset to understand its structure.
- Selected **Annual Income** and **Spending Score** as key features for clustering.
- Standardized these features to have zero mean and unit variance.
- Used the **Elbow Method** to determine the optimal number of clusters, which was found to be 5.
- Applied **K-Means clustering** to segment the customers into 5 groups.
- Evaluated clustering quality using the **Silhouette Score**.
- Visualized the clusters with color-coded scatter plots along with their centroids.
- Included an optional PCA-based 2D visualization when more features are used.

## Results

- The segmentation reveals distinct customer groups based on income and spending habits.
- Silhouette Score indicates reasonably good cluster separation.
- Visualizations help interpret and compare customer segments for potential marketing strategies.

---
