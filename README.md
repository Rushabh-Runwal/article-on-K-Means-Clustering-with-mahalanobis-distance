# **K-Means Clustering with Incomplete Data Using Mahalanobis Distance**

## **Overview**
This repository contains:
- A Python implementation of the unified K-Means algorithm enhanced with Mahalanobis distance to handle incomplete data.
- A Medium article summarizing the key concepts, algorithm, and results.
- A presentation deck to explain the algorithm, experiments, and results visually.

---

## **Abstract**
Effectively applying the K-Means algorithm to datasets with missing values is an important research challenge. Traditional methods often separate data imputation and clustering, leading to suboptimal results. This project implements and extends the unified K-Means algorithm to incorporate **Mahalanobis distance**, which is better suited for elliptical clusters.

Key contributions:
1. Unified clustering and imputation in one framework.
2. Replacement of Euclidean distance with Mahalanobis distance for improved accuracy on non-spherical clusters.
3. Experimental validation showing superior performance in Adjusted Rand Index (ARI) and Normalized Mutual Information (NMI) metrics across synthetic and real-world datasets.
