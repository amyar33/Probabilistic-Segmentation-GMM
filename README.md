# Probabilistic Customer Segmentation using Gaussian Mixture Models

## Overview
This repository implements a probabilistic clustering framework using **Gaussian Mixture Models (GMM)**. Unlike K-Means, which performs hard assignments, this project utilizes the **Expectation-Maximization (EM)** algorithm to perform 'soft' clustering, allowing for a more nuanced understanding of overlapping behavioral segments in demographic data.

## Technical Methodology
* **Probabilistic Modeling:** Leveraged GMM to account for cluster covariance and non-spherical data distributions.
* **Model Selection:** Utilized **Bayesian Information Criterion (BIC)** and **Akaike Information Criterion (AIC)** to determine the optimal number of components, preventing over-complexity.
* **Dimensional Analysis:** Clustered high-dimensional features (Annual Income, Spending Score) to identify high-value consumer groups.

## Key Insights
* Identified 5 distinct consumer archetypes through BIC-optimized component selection.
* The GMM approach provided probability density estimations for each segment, highlighting areas of demographic overlap that traditional clustering methods miss.



## Structure
* `Customer_Segmentation_GMM_Analysis.ipynb`: Full modeling pipeline.
* `Mall_Customers.csv`: Dataset used for the case study.
* `requirements.txt`: Environment dependencies.
