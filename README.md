# Product Demand & Inventory Intelligence

## Project Overview
This project uses machine learning to analyze product demand and inventory patterns. It applies unsupervised learning techniques to group products with similar characteristics and support inventory planning decisions.

## Objectives
- Perform exploratory data analysis (EDA).
- Clean and preprocess the dataset.
- Standardize numerical features.
- Apply K-Means clustering and use the Elbow Method to examine cluster counts.
- Compare K-Means with Hierarchical Clustering.
- Visualize clusters using PCA.
- Evaluate clustering using the Silhouette Score and Davies–Bouldin Index.
- Develop preliminary business recommendations from the results.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- SciPy
- Google Colab

## Methods
The project aggregates records at the product level, scales selected numerical features, applies clustering algorithms, and evaluates the resulting groups using internal clustering metrics.

## Dataset
The project uses retail inventory and demand data. The dataset contains fields such as product category, inventory level, units sold, units ordered, price, discount, and demand.

## How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Upload the dataset to the expected Google Drive location or update the dataset path in the notebook.
3. Run the notebook cells from top to bottom.

## Limitations
This project performs unsupervised product segmentation; it does not train a supervised model to forecast future demand. Business recommendations should be validated against store-level trends, stockouts, lead times, and profitability.

## Author
Anshika Yadav
