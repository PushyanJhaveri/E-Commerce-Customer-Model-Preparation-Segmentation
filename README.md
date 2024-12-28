# E-Commerce-Customer-Model-Preparation-Segmentation
1. Data Cleaning & Transformation:
Handle missing values, duplicates, and outliers to prepare a clean dataset.
2. Feature Engineering:
Create customer-centric features like TotalAmount and engineered time-based features.
3. Data Preprocessing:
Scale numerical features and encode categorical variables to standardize the dataset.
4. Model preparation:
Splitting the dataset in test and train.

Features of the Project
1. Data Cleaning and Transformation
Removed missing values in critical columns (e.g., CustomerID).
Filled missing product descriptions with "Unknown."
Handled duplicates and filtered out negative quantities and unit prices.
Created new features like TotalAmount (Quantity × UnitPrice).
2. Feature Engineering
Applied one-hot encoding for categorical variables like Country.
Engineered time-based features such as Year, Month, Day, and Hour.
Performed dimensionality reduction using PCA for clustering.
3. Data Preprocessing
Normalized numerical features using Min-Max scaling for clustering.
Standardized features with zero mean and unit variance for classification.
4. Model preparation:

Dimensionality Reduction using PCA:
Principal Component Analysis (PCA) reduces features to 2 dimensions for better visualization and clustering efficiency.
Added PCA components (PCA_1, PCA_2) to the dataset for downstream analysis.

Data Splitting:
Ensures proper splitting of the dataset into training, validation, and test sets.
Uses stratified sampling to maintain class balance for the classification task.
Target column (Cluster) is either pre-existing or simulated.


Requirements
To run this project, you will need:

Python 3.8 or higher
Libraries:
pandas
numpy
matplotlib
scikit-learn
