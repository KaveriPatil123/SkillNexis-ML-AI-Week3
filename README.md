# SkillNexis ML & AI Internship – Week 3

## Iris Flower Clustering Project

This project is completed as part of the SkillNexis Machine Learning & AI Internship – Week 3.

The project demonstrates unsupervised learning using K-Means Clustering and Principal Component Analysis (PCA) on the Iris dataset.

## Project Objectives

- Apply K-Means Clustering on the Iris dataset
- Create 3 clusters using K = 3
- Visualize the clusters
- Apply PCA to reduce the dataset to 2 dimensions
- Calculate explained variance ratio
- Compare predicted clusters with true Iris species
- Save and load the trained model

## Dataset

The project uses the Iris dataset containing 150 samples and 4 numerical features.

### Features Used

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Species

- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- K-Means Clustering
- PCA
- Pickle

## Project Steps

### 1. Data Loading

The Iris dataset is loaded using Pandas and the required numerical features are selected.

### 2. Data Scaling

The four numerical features are standardized before applying clustering and PCA.

### 3. K-Means Clustering

K-Means clustering is applied with:

```text
K = 3
