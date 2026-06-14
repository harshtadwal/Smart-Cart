# Smart-Cart
Smart Cart is an Unsupervised Machine Learning project that analyzes customer shopping behavior using clustering techniques.

The project identifies meaningful customer groups by applying:

- K-Means Clustering
- Agglomerative Clustering

To determine the optimal number of clusters, the following methods are used:

- Elbow Method
- Silhouette Score Analysis

---

## Objectives

- Perform customer segmentation.
- Determine the optimal number of clusters.
- Compare clustering techniques.
- Visualize customer groups.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Dataset

The dataset contains customer shopping-related features used for clustering analysis.

---

## Methodology

### 1. Data Preprocessing

- Handling missing values
- Feature selection
- Data normalization

### 2. Optimal K Selection

#### Elbow Method

Used to find the point where adding more clusters provides diminishing returns.

#### Silhouette Score

Measures cluster quality and separation.

### 3. Clustering Algorithms

#### K-Means Clustering

Partitions data into K clusters by minimizing within-cluster variance.

#### Agglomerative Clustering

Hierarchical clustering approach that merges similar clusters iteratively.

---

## Results

The clustering results reveal distinct customer segments based on purchasing patterns.

Performance comparison between:

- K-Means
- Agglomerative Clustering

was conducted using clustering evaluation metrics and visualizations.

---
