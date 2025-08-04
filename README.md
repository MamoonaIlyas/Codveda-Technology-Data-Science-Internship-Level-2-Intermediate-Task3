# Codveda-Technology-Data-Science-Internship-Level-2-Intermediate-Task3
Task 3: Clustering (Unsupervised  Learning)

🛍️ Mall Customer Segmentation using K-Means Clustering
Task 3 - Level 2 | Data Science Internship at CodVeda Technology

This project applies K-Means Clustering to segment mall customers based on their annual income and spending score, helping businesses identify distinct customer groups for better marketing and service strategies.

📌 Objective
To implement unsupervised machine learning using K-Means clustering on real-world customer data and discover hidden patterns or groupings among customers.

📁 Dataset
Name: Mall Customers Dataset

Source: Kaggle – Customer Segmentation Dataset

Features Used:

Annual Income (k$)

Spending Score (1-100)

Age (for interpretation)

Gender (for categorical analysis)

⚙️ Workflow Overview
Data Preprocessing

Feature selection

Scaling with StandardScaler

Finding Optimal Clusters

Elbow Method

Silhouette Score

K-Means Clustering

Assign clusters to each customer

Analyze and interpret cluster characteristics

Visualization

2D scatter plot of customer clusters

Cluster centers in original and scaled form

PCA for dimensionality reduction (if needed)

Cluster Interpretation

Numerical summaries (Income, Spending Score, Age)

Gender distribution per cluster

Business insights for each segment

📊 Key Results
Optimal K Selected: 5

Clusters show clear separation between:

High spenders vs frugal buyers

Affluent but careful vs impulsive shoppers

Used cluster center values to interpret business-relevant customer traits.

📦 Libraries Used
Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (KMeans, PCA, silhouette_score, StandardScaler)

📌 Insights
Identified actionable segments such as:

🎯 High-income, high-spending customers (target group)

💸 Low-income but high-spending customers (impulsive buyers)

💰 High-income but low-spending customers (careful spenders)

📂 Files Included
Mall_Customers.csv – Dataset

clustering_task3.py – Full implementation

README.md – This documentation
