# 🛍️ Customer Segmentation using K-Means Clustering

This project applies unsupervised machine learning to segment mall customers based on their Annual Income and Spending Score. The goal is to identify distinct customer groups to help with targeted marketing and business insights.

---

## 📁 Dataset

The dataset contains mall customer data with features like:

- Customer ID
- Genre (Gender)
- Age
- Annual Income (k$)
- Spending Score (1–100)

> 📂 File used: Mall_Customers.csv

---

## 🔧 Steps Performed

1. Data Exploration  
   - Loaded dataset and examined basic statistics.  
   - Visualized relationships between features (income vs. spending score).

2. Feature Selection  
   - Selected Annual Income (k$) and Spending Score (1–100) for clustering.

3. Feature Scaling  
   - Applied StandardScaler to ensure both features contribute equally to distance calculations.  
   - Reason: K-Means is distance-based, so scaling avoids bias from different ranges.

4. Finding Optimal Clusters  
   - Used the Elbow Method to determine the best value of *k*.

5. K-Means Clustering  
   - Trained the model with the chosen number of clusters.  
   - Assigned each customer to a cluster.

6. Visualization  
   - Created 2D scatter plots to visualize clusters and centroids.

7. Cluster Analysis  
   - Calculated average income and spending score for each group.

---

## 📊 Visualizations

- 📈 Scatter plot showing the relationship between Annual Income and Spending Score (before clustering).  
- 📉 Elbow Method graph to determine the optimal number of clusters.  
- 🎨 Scatter plot of customer segments after applying K-Means, with cluster centroids highlighted.

---

## 📦 Libraries Used

```bash
pandas
scikit-learn
matplotlib
