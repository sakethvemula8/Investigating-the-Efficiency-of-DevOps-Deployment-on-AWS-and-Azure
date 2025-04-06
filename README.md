# Investigating-the-Efficiency-of-DevOps-Deployment-on-AWS-and-Azure

## Overview

This project is part of my Master's capstone and focuses on evaluating and optimizing the efficiency of DevOps deployments across two major cloud platforms: Amazon Web Services (AWS) and Microsoft Azure.

Through quantitative data analysis, I explore key performance indicators such as deployment time, resource usage, scalability, and reliability, aiming to identify inefficiencies and provide data-driven recommendations for optimizing cloud-native DevOps workflows.

## Problem Statement

Despite widespread adoption of DevOps and cloud technologies, many organizations face:

- Long deployment times
- Excessive resource consumption
- Inconsistent platform performance

This project aims to analyze the efficiency of cloud-based DevOps practices on AWS and Azure to derive optimization insights.

## Objective 

- Analyze DevOps performance across AWS and Azure using real-world deployment data.
- Identify key correlations (e.g., between deployment time and resource usage).
- Apply machine learning models to:
  - Predict deployment durations
  - Cluster deployment scenarios
  - Recommend optimized deployment strategies for each cloud platform.
 
## Methodology

- Techniques Used:
  - Exploratory Data Analysis (EDA)
  - Correlation Analysis
  - Visualization (Histograms, Heatmaps, Scatter Plots)
  - Machine Learning:
    - Regression (Linear, Decision Tree, Random Forest, Gradient Boosting)
    - Clustering (K-Means, Hierarchical, DBSCAN)

## Insights So Far

- High correlation (0.99) between deployment time and resource usage — indicating that optimization in time directly reduces cloud costs.
- Efficiency Score is positively correlated with both AWS Scalability (0.72) and Azure Reliability (0.71).
- Visualization shows most deployments range between 20–80 hours and resource consumption follows a similar pattern.


## In Progress

I'm currently working on:
- Enhancing the predictive modeling pipeline with advanced regressors.
- Exploring Gaussian Mixture Models and Agglomerative Clustering to outperform K-Means.
- Planning to implement neural networks for deeper pattern extraction and improved accuracy.
- Adding real-time cloud monitoring data in the next phase.











