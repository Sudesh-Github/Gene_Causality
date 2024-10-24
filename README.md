# Gene Causality Detection Using Embeddings and Clustering

This project aims to identify patterns in gene-phenotype pairs to differentiate between causal and non-causal pairs using embedding techniques and clustering analysis. The project uses machine learning models and silhouette scoring to evaluate the separation between these gene-phenotype pairs.

## Project Overview

In this project, we use embeddings to represent gene-phenotype pairs and cluster them to detect causal and non-causal relationships. The main goal is to assess the separation between these two types of pairs and explore insights from the clustering results.

### Key Features
- Utilize pre-trained embeddings or fine-tuned embeddings for gene-phenotype pairs.
- Perform clustering using methods like KMeans.
- Evaluate clustering performance using the silhouette score.
- Visualize and interpret the clusters for causal and non-causal pairs.

## Table of Contents
1. [Installation](#installation)
2. [Data](#data)
3. [Usage](#usage)
4. [Evaluation](#evaluation)
5. [Future Work](#future-work)
6. [Contributors](#contributors)

## Installation

To run this project, you need to have Python 3.x installed, along with the following packages:

```bash
pip install numpy pandas scikit-learn matplotlib
