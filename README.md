# Clustering-with-K-Means
# Unsupervised Learning with K-Means Clustering

This project demonstrates the use of **K-Means clustering** for unsupervised learning on the **Mall Customers dataset**. The objective is to segment customers into groups based on their demographic and spending behavior, using key features such as age, annual income, and spending score.

## Tools & Libraries:
- **Python**
- **Pandas** for data manipulation
- **Matplotlib** for data visualization
- **Scikit-learn** for K-Means, PCA, and evaluation metrics

## Workflow:
1. **Load and Explore the Data**: Understand the structure and clean the dataset.
2. **Feature Selection & Preprocessing**: Standardize selected features (`Age`, `Annual Income`, `Spending Score`).
3. **Dimensionality Reduction**: Use PCA for 2D visualization of clusters.
4. **K-Means Clustering**: Apply K-Means to segment customers.
5. **Elbow Method**: Determine the optimal number of clusters using inertia.
6. **Silhouette Score**: Validate clustering quality and select best `K`.
7. **Visualization**: Plot final clusters in 2D space for interpretability.

## Results:
- Optimal number of clusters was determined using both **Elbow Method** and **Silhouette Score**.
- Final visualization provides intuitive insight into customer segments.
