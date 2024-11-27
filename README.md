# **K-Means Clustering with Incomplete Data Using Mahalanobis Distance**

## **Reserch Paper and arxiv URL**  https://arxiv.org/abs/2411.00870

## **Abstract**
Effectively applying the K-means algorithm to data with missing values remains an important research
area due to its impact on applications that rely on K-means clustering. Recent studies have shown
that integrating imputation directly into the K-means algorithm yields superior results compared to
handling imputation separately.
In this work, we extend this approach by developing a unified K-means algorithm that incorporates
Mahalanobis distances, instead of the traditional Euclidean distances, which previous research has
shown to perform better for clusters with elliptical shapes.
We conduct extensive experiments on synthetic datasets containing up to ten elliptical clusters, as well
as the IRIS dataset. Using the Adjusted Rand Index (ARI) and Normalized Mutual Information (NMI),
we demonstrate that our algorithm consistently outperforms both standalone imputation followed
by K-means (using either Mahalanobis or Euclidean distance) and recent K-means algorithms that
integrate imputation and clustering for handling incomplete data. These results hold across both the
IRIS dataset and randomly generated data with elliptical clusters.

## **Overview**
This repository contains:
- [A Medium article summarizing the key concepts, algorithm, and results.](https://medium.com/@rushabh22runwal/k-means-clustering-with-incomplete-data-with-the-use-of-mahalanobis-distances-83d79aa5393b)
- [A presentation deck to visually explain the algorithm, experiments, and results.](https://www.slideshare.net/slideshow/k-means-clustering-with-incomplete-data-_using-mahalanobis-distance-pptx/273656228)

---

Key contributions:
1. Unified clustering and imputation in one framework.
2. Replacement of Euclidean distance with Mahalanobis distance for improved accuracy on non-spherical clusters.
3. Experimental validation showing superior performance in Adjusted Rand Index (ARI) and Normalized Mutual Information (NMI) metrics across synthetic and real-world datasets.


Experiments and Results
Datasets
- Iris Dataset: A benchmark dataset for testing clustering algorithms.
- Synthetic Data: Randomly generated elliptical clusters with 10%-50% missing values.

Performance Metrics
- Adjusted Rand Index (ARI): Measures clustering accuracy.
- Normalized Mutual Information (NMI): Quantifies agreement between true labels and clustering results.

Key Findings
- Robust to Missing Data: Achieves high ARI even with 50% missing data.
- Better for Elliptical Clusters: Outperforms traditional K-Means in clustering non-spherical data.


Contributors
- [Lovis Kwasi Armah](https://www.linkedin.com/in/armahlovis/)
- [Igor Melnykov](https://www.linkedin.com/in/igor-melnykov-b38789106/)
