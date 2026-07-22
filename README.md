# clustering-of-text-documents

An unsupervised machine learning project that clusters health-related tweets using multiple clustering algorithms and compares their performance.

## Overview

This project processes a collection of Twitter posts, converts the text into numerical feature vectors using a Bag-of-Words representation, computes similarity and distance metrics, and applies several clustering techniques to discover natural groupings within the data.

The clustering methods are evaluated using standard metrics and visualized with PCA to compare their performance.

## Features

* Text preprocessing and Bag-of-Words feature extraction
* Cosine similarity and Jaccard distance computation
* Multiple clustering algorithms:

  * K-Means
  * DBSCAN
  * Agglomerative Clustering
  * Spectral Clustering
* Clustering evaluation using:

  * Silhouette Score
  * Cohesion and Separation
  * Entropy and Purity
* PCA visualizations of clustering results
* Automatic extraction of the most common words from a selected cluster

## Technologies

* Python
* NumPy
* scikit-learn
* Matplotlib

## Running the Project

1. Install the required packages:

```bash
pip install numpy scikit-learn matplotlib
```

2. Place `cnnhealth.txt` in the project directory.

3. Run:

```bash
python clustering.py
```

The script generates feature matrices, similarity/distance matrices, clustering results, evaluation metrics, and PCA visualizations.
