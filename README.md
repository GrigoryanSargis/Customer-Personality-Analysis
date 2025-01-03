# Customer-Personality-Analysis
## Overview
This project explores customer segmentation using machine learning techniques to identify groups based on:

Spending patterns
Campaign responsiveness
Demographic factors
Two major approaches were used:

PCA with K-Means Clustering: For variance-based segmentation and efficiency.
NMF with GMM: For interpretable latent factors and probabilistic clustering.

## Features
Dimensionality Reduction:

* PCA for variance maximization.
* NMF for interpretable component extraction.

Clustering Algorithms:

* K-Means for hard clustering.
* GMM for probabilistic clustering.

Visualization Tools:

* Explained variance plots.
* Heatmaps of NMF components.
* Cluster distribution visualizations.

## Dataset
The dataset contains customer attributes such as:

Demographics: Income, Age, Children, etc.

Spending: MntWines, MntMeatProducts, etc.

Campaign Participation: AcceptedCmp1, AcceptedCmp2, etc.

## Results
* PCA with K-Means:
* * Optimal clusters: 4
* * Explained variance: 58% with 2 components.
* NMF with GMM:
** Optimal clusters: 3
I** nterpretable components for spending, demographics, and campaign engagement.

Detailed visualizations and cluster profiles included in the notebook.
