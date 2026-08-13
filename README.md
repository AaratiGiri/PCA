![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-PCA-orange)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-PCA-F7931E?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

# PCA — Wine Dataset

## Overview

This project demonstrates **Principal Component Analysis (PCA)** using the Wine dataset available in `scikit-learn`.

The notebook covers the basic steps of applying PCA to reduce the dimensionality of the dataset while preserving as much information as possible.

## Dataset

The project uses the **Wine dataset** from `scikit-learn`.

- **Samples:** 178
- **Features:** 13
- **Target classes:** 3
- **Missing values:** None

## Project Steps

1. Import required libraries
2. Load the Wine dataset
3. Explore the dataset and feature names
4. Create a Pandas DataFrame
5. Check dataset information and missing values
6. Perform basic statistical analysis
7. Separate features and target
8. Standardize the features using `StandardScaler`
9. Apply PCA with 2 components
10. Calculate explained variance
11. Visualize the transformed data using PC1 and PC2

## PCA Results

The PCA was performed with **2 components**.

- **PC1 explained variance:** 36.20%
- **PC2 explained variance:** 19.21%
- **Total variance explained:** **55.41%**

The final visualization shows the Wine data projected onto the first two principal components.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## File

| File | Description |
|------|-------------|
| `pca.ipynb` | Complete PCA analysis, preprocessing, and visualization |

## Learning Objective

The main objective of this project is to understand how **Principal Component Analysis (PCA)** can be used for:

- Dimensionality reduction
- Feature transformation
- Data visualization
- Understanding explained variance

## Conclusion

PCA reduced the original **13 features to 2 principal components**, with the first two components explaining approximately **55.41% of the total variance** in the dataset.

The resulting 2D representation makes it easier to visualize the structure of the Wine dataset.
