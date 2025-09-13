# 📊 Customer Segmentation Analysis

This project performs customer segmentation on a mall customer dataset to identify distinct groups based on their spending habits and income. The analysis uses two popular clustering algorithms: **K-Means Clustering** and **DBSCAN**.

Project Overview Section

### 📌 Project Overview

- **Exploratory Data Analysis (EDA)**: Performed initial data exploration, visualization, and outlier detection.
- **K-Means Clustering**: Applied K-Means to group customers and used the **Elbow Method** to find the optimal number of clusters.
- **DBSCAN**: Implemented DBSCAN to find density-based clusters and identify potential outliers.
- **Cluster Analysis**: Analyzed and interpreted the characteristics of each cluster to understand customer behavior.

Tech Stack Section

### 🛠️ Tech Stack

- **Python**
- **NumPy, Pandas**: For data manipulation and analysis.
- **Matplotlib, Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning and clustering algorithms.

Dataset Section

### 📂 Dataset

The analysis is based on the `Mall_Customers.csv` dataset, which includes the following features:

- `CustomerID`
- `Genre`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

Exploratory Data Analysis

### 📊 Exploratory Data Analysis

- Checked for missing values and duplicates.
- Visualized the distribution of `Annual Income` and `Spending Score`.
- Created scatter plots to visualize the data points and initial potential clusters.

Models Implemented

### 🤖 Models Implemented

- **K-Means Clustering**: A centroid-based algorithm used to partition the data into a predefined number of clusters.
- **DBSCAN**: A density-based algorithm that discovers clusters of arbitrary shapes and is effective at identifying noise points.

Model Evaluation

### 📈 Model Evaluation & Analysis

- The results of both clustering algorithms are evaluated by examining the final clusters' characteristics.
- The final analysis provides insights into different customer segments, such as "High Income, Low Spending" or "Average Income, Average Spending," which can be used for targeted marketing strategies.

Visualizations

### 📷 Visualizations

- **Elbow Method Plot**: Used to determine the optimal number of clusters for K-Means.
- **K-Means Clustering Plot**: Visual representation of the K-Means clusters.
- **DBSCAN Clustering Plot**: Visual representation of the DBSCAN clusters.
