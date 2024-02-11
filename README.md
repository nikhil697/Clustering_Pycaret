# Clustering Analysis with PyCaret

## Introduction
This repository contains a Python script for clustering analysis using the PyCaret library. The analysis is performed on a dataset of mall customers with various clustering algorithms, including K-Means, Hierarchical, and Birch. The script explores different preprocessing techniques and evaluates the models with various numbers of clusters.

## Prerequisites
Ensure you have the required Python libraries installed. You can install them using the following command:
```bash
!pip install pycaret &> /dev/null
```

## Usage
<ol><li>Install the necessary libraries.
<li>Execute the provided Python script in a Jupyter notebook or any Python environment.
<li>The script loads the dataset, performs clustering analysis, and evaluates different clustering algorithms.
<li>Results are visualized using 2D plots, 3D plots, elbow plots, silhouette plots, and distribution plots.</ol><br>
  
## Files
<ol><li><a href="https://github.com/nikhil697/Clustering_Pycaret/blob/main/Clustering_pycaret.ipynb">clustering_pycaret.ipynb</a>: Jupyter notebook containing the clustering analysis script.
  <li><a href="https://github.com/nikhil697/Clustering_Pycaret/blob/main/Mall_Customers.csv">Mall_Customers.csv</a>: Csv File containing dataset.
<li><a href="https://github.com/nikhil697/Clustering_Pycaret/blob/main/kmeanprediction.csv">kmeanprediction.csv</a>: CSV file containing predictions from the K-Means clustering model.</ol>

## Clustering Models Explored
<ol><li>K-Means
<li>Hierarchical Clustering
<li>Birch</ol>

## Preprocessing Techniques Explored
<ol><li>Normalization
<li>Transformation
<li>PCA (Principal Component Analysis)
<li>Combination of Transformation + Normalization
<li>Combination of Transformation + Normalization + PCA</ol>

## Results
<p>The script generates various visualizations to analyze the performance of clustering models under different preprocessing scenarios. 
The silhouette score is used as a metric for evaluating clustering performance.</p>

## Conclusion
Summarize the key findings from the analysis and any insights gained.
