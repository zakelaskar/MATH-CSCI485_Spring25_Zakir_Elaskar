Overview:
This project applies Principal Component Analysis (PCA) and t-SNE to the UCI Wine Quality dataset to explore dimensionality reduction techniques and visualize high-dimensional data.


Dataset:
The dataset is obtained from the UCI Machine Learning Repository and contains physicochemical properties of red and white wine samples, along with their quality ratings.


Implementation Steps:
1. Data Preprocessing:


•	Load red and white wine datasets.

•	Combine both red and white wine data.

•	Normalize features using StandardScaler.

2. PCA Analysis:

•	Apply PCA to reduce dimensions to 2D and 3D.

•	Compute explained variance.

•	Visualize PCA results with scatter plots.

3. t-SNE Analysis:

•	Apply t-SNE for 2D representation.

•	Compare t-SNE with PCA in terms of clustering and interpretability.

4. Results & Discussion:

•	Discuss the trade-offs between PCA and t-SNE.

•	Compare how each method handles high-dimensional data.

•	PCA captures global variance but may not highlight clusters well.

•	t-SNE preserves local structure but is computationally intensive.

•	Visual comparisons provided in the notebook.


