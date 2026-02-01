# Machine Learning Algorithms - From Scratch

This repository contains implementations of various machine learning algorithms built from scratch using Python and NumPy. These implementations were created as part of my Machine Learning course to understand the mathematical foundations behind each algorithm.

## Overview

The goal of this project is to implement ML algorithms without relying on high-level libraries like scikit-learn. Each notebook includes:
- Custom implementation of the algorithm
- Mathematical foundations applied in code
- Visualizations of results
- Testing on synthetic/sample datasets

## Algorithms Implemented

### Clustering Algorithms

| Notebook | Algorithm | Description |
|----------|-----------|-------------|
| `1_kmeans_clustering.ipynb` | K-Means | Partitioning method that divides data into k clusters by minimizing within-cluster variance |
| `2_hierarchical_clustering.ipynb` | Hierarchical Clustering | Agglomerative approach building a hierarchy of clusters using linkage methods |
| `3_self_organizing_map.ipynb` | Self-Organizing Map (SOM) | Neural network-based technique for dimensionality reduction and visualization |
| `4_dbscan.ipynb` | DBSCAN | Density-based clustering that can find arbitrarily shaped clusters and identify outliers |
| `5_fuzzy_c_means.ipynb` | Fuzzy C-Means | Soft clustering where each point has a degree of membership to each cluster |

### Neural Networks

| Notebook | Algorithm | Description |
|----------|-----------|-------------|
| `6_perceptron.ipynb` | Perceptron | Single-layer neural network for binary classification |
| `7_multilayer_neural_network.ipynb` | Multilayer Perceptron | Feedforward neural network with backpropagation for training |
| `8_recurrent_neural_network.ipynb` | Recurrent Neural Network | Neural network with loops for sequential data processing |

### Classification & Evaluation

| Notebook | Algorithm | Description |
|----------|-----------|-------------|
| `9_support_vector_machine.ipynb` | Support Vector Machine | Maximum margin classifier with kernel trick for non-linear boundaries |
| `10_evaluation_metrics.ipynb` | Evaluation Metrics | Implementation of accuracy, precision, recall, F1-score, confusion matrix |

## Requirements

```
numpy
matplotlib
```

## Installation

```bash
# Clone the repository
git clone <repo-url>
cd Learning-ML

# Install dependencies
pip install numpy matplotlib
```

## Usage

Open any notebook in Jupyter and run all cells:

```bash
jupyter notebook
```

Each notebook is self-contained and can be run independently.

## Project Structure

```
Learning ML/
├── 1_kmeans_clustering.ipynb
├── 2_hierarchical_clustering.ipynb
├── 3_self_organizing_map.ipynb
├── 4_dbscan.ipynb
├── 5_fuzzy_c_means.ipynb
├── 6_perceptron.ipynb
├── 7_multilayer_neural_network.ipynb
├── 8_recurrent_neural_network.ipynb
├── 9_support_vector_machine.ipynb
├── 10_evaluation_metrics.ipynb
└── README.md
```

## Acknowledgments

These implementations were created as part of coursework to gain a deeper understanding of how machine learning algorithms work under the hood.
