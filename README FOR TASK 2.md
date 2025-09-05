# Customer Segmentation with K-Means

This project applies unsupervised machine learning to cluster customers into distinct groups based on their **annual income** and **spending score**, using the **Mall Customers dataset** from Kaggle. The goal is to segment customers into meaningful groups for targeted marketing strategies and better business decision-making.

✨ **Features**

* **Data Cleaning & Exploration 📂**: Loaded the dataset and explored summary statistics.
* **Visualization 📊**: Histograms and scatter plots to understand customer distributions.
* **Feature Selection ✂️**: Focused on **Age**, **Annual Income (k\$)**, and **Spending Score (1–100)**.
* **K-Means Clustering 🤖**: Applied K-Means to partition customers into segments.
* **Optimal Clusters 🔍**: Used evaluation techniques (Elbow method / Silhouette score) to determine the best number of clusters.
* **Cluster Visualization 🎨**: Plotted customer segments in 2D space for interpretability.

🚀 **Getting Started**

1. Place the dataset `Mall_Customers.csv` in your working directory.
2. Run the notebook or Python script to:

   * Load and preprocess the dataset.
   * Apply K-Means clustering.
   * Evaluate optimal cluster count.
   * Visualize customer segments.

📊 **Results**

* Customers are successfully segmented into distinct groups based on their income and spending behavior.
* A dendogram was plotted as well
* 2D scatter plots highlight the clusters, showing clear separation of customer categories.
* The optimal number of clusters ensures meaningful segmentation for marketing insights.

