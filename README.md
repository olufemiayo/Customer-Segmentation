# Unsupervised Learning
Customer Segmentation Using K-Means Clustering

📌 **Project Overview**

This project applies unsupervised machine learning to segment customers based on their Annual Income and Spending Score. Using K-Means clustering, customers are grouped into distinct segments that reveal behavioral patterns and business opportunities.

The goal is to help businesses:

Understand customer behavior

Identify high-value customers

Design targeted marketing strategies

Optimize resource allocation

📊 **Dataset Description**

The dataset contains customer demographic and behavioral features, including:

Annual Income (k$) – Customer’s yearly income

Spending Score (1–100) – Score assigned based on purchasing behavior

These features are commonly used in marketing analytics to understand purchasing power and spending habits.

🛠️ **Tools & Technologies**

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib / Seaborn – Data visualization

Scikit-learn – K-Means clustering

🔍 **Methodology**

1️⃣ Data Exploration

Checked for missing values

Explored distributions of income and spending

Visualized relationships between features

2️⃣ Feature Selection

Selected Annual Income and Spending Score for clustering

Scaled features where necessary

3️⃣ Optimal Number of Clusters

Used the Elbow Method to determine the optimal value of K

4️⃣ K-Means Clustering

Applied K-Means algorithm

Assigned each customer to a cluster

Computed cluster centroids

📈 **Cluster Summary & Insights**

| Cluster | Avg Income (k$) | Avg Spending Score | Customer Type                     |
| ------- | --------------- | ------------------ | --------------------------------- |
| 0       | 55.3            | 49.5               | Average income, average spending  |
| 1       | 86.5            | 82.1               | High income, high spending (VIPs) |
| 2       | 25.7            | 79.4               | Low income, high spending         |
| 3       | 88.2            | 17.1               | High income, low spending         |
| 4       | 26.3            | 20.9               | Low income, low spending          |

📌 **Key Takeaways**

Customer behavior varies significantly even with similar income levels

Spending patterns are not always income-dependent

Segmentation enables data-driven marketing decisions

Unsupervised learning is powerful for discovering hidden patterns
