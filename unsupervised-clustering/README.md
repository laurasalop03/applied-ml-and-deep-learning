# Unsupervised Learning: Customer Segmentation & Market Basket Analysis

This directory focuses on unsupervised algorithms for retail analytics, applying K-Means clustering to segment mall customers and utilizing association rule mining to discover product dependencies in grocery transactions.

### Algorithmic & Engineering Highlights
* **Robust Outlier Removal:** Applied Interquartile Range (IQR) mathematical filtering to identify and drop high-income anomalies, preventing spatial distortion and centroid skewing in distance-based clustering.
* **Optimal 'k' Selection:** Computationally evaluated cluster cohesion using the Elbow Method (WCSS inertia) and Silhouette Scores, testing solutions across both 2D and 3D feature spaces.
* **Categorical Encoding:** Enforced `StandardScaler` normalization alongside `LabelEncoder` transformations to map categorical string variables (e.g., Gender) into binary representations without corrupting the geometric space.
