 Customer Segmentation using K-Means Clustering

Objective
To perform unsupervised learning using *K-Means clustering* to identify distinct customer groups for marketing and business insights.

 Dataset Used
*Mall_customer.csv*  
Features considered:
- Annual Income (k$)
- Spending Score (1-100)

 Technologies & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

 Steps Performed

1. *Loaded the Dataset* using Pandas.
2. *Selected Relevant Features*: Annual Income and Spending Score.
3. *Standardized the Data* using StandardScaler.
4. *Used Elbow Method* to find the optimal number of clusters (k).
5. *Applied K-Means Clustering* using Scikit-learn.
6. *Visualized the Clusters* using Matplotlib & Seaborn.
7. *Evaluated Clustering* with *Silhouette Score*.

 Elbow Method Plot
Used to determine the best value of k by observing the "elbow" point in the inertia plot.

 Cluster Visualization
Clusters are color-coded based on:
- Annual Income (X-axis)
- Spending Score (Y-axis)

 Evaluation
- *Silhouette Score* used to assess how well the clusters are defined.
- Higher score = better-defined clusters.

 Screenshots
Add plots of:
- Elbow Method
- Cluster Visualization


