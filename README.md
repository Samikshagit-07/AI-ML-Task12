# AI-ML-Task12

Project Overview

The goal of this project is to perform unsupervised learning to segment customers of a mall based on their annual income and spending patterns. This helps businesses understand different customer personas and tailor their marketing strategies accordingly

Tools Used

Language: Python 

Libraries: Scikit-learn, Pandas, Matplotlib, Seaborn 

Algorithm: KMeans Clustering

Workflow 

Data Loading: Loaded the Mall Customer Segmentation dataset.

Preprocessing: Dropped the CustomerID column as it does not contribute to clustering.

Feature Scaling: Applied StandardScaler to ensure the income and spending score features are on the same scale for accurate distance calculation.

Optimal K Selection: Used the Elbow Method by plotting inertia values for $K$ values from 1 to 10.

Model Training: Trained the KMeans model using the optimal $K$ value identified from the elbow plot.

Visualization: Plotted the final clusters to visualize customer segments

Results & Deliverables

Elbow Plot: Used to determine the "bend" where increasing clusters no longer significantly reduces inertia.

Cluster Visualization: A scatter plot showing 5 distinct customer groups.

Segmented Dataset: The final output file Segmented_Mall_Customers.csv includes the cluster labels for each customer.

Customer Segments Identified

Target Customers: High Income, High Spending Score.

Careful Customers: High Income, Low Spending Score.

Standard Customers: Average Income, Average Spending Score.

Impulsive Customers: Low Income, High Spending Score.

Sensible Customers: Low Income, Low Spending Score
