# Iris Flower Clustering with K-Means

## Overview
This Python script demonstrates the application of the K-Means clustering algorithm on the Iris dataset. The script uses Pandas for data manipulation, Matplotlib for data visualization, and scikit-learn for K-Means clustering and performance evaluation. It visualizes the original Iris dataset, performs K-Means clustering, and evaluates the accuracy of the clustering.

## Prerequisites
Make sure you have the required libraries installed. You can install them using the following command:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/rajinmail/iris-clustering.git
cd iris-clustering
```

2. Run the script:

```bash
python iris_clustering.py
```

## Code Description
- **Load Iris dataset:**
  - Loads the Iris dataset from scikit-learn and converts it into Pandas DataFrames.

- **Visualize the Data:**
  - Creates scatter plots to visualize the Sepal Length vs Sepal Width and Petal Length vs Petal Width.

- **K-Means Clustering:**
  - Creates a K-Means model with 3 clusters and fits it to the data.

- **Visualize Clustering Results:**
  - Displays scatter plots before and after classification using K-Means.

- **Evaluate Model Accuracy:**
  - Calculates the accuracy of the K-Means clustering model.

- **Confusion Matrix:**
  - Generates and prints the confusion matrix for the clustering results.

## Results
The script outputs visualizations of the original data and the data after K-Means clustering. It also provides the accuracy of the clustering and the confusion matrix, allowing you to assess how well the K-Means algorithm has grouped the Iris flowers into clusters.

Feel free to experiment with the number of clusters and explore different aspects of the clustering results. You can further modify the script to apply K-Means clustering to other datasets or adapt it for different clustering tasks.
