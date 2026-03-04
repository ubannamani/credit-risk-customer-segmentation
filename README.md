# Customer Risk Segmentation using Clustering

## Overview
This project applies unsupervised learning to segment credit card customers based on repayment behavior.

The goal is to identify high-risk and low-risk customer groups for better financial decision-making.

## Dataset
- Source: UCI Machine Learning Repository
- Records: 30,000
- Features: 25 (numerical)
- Target removed (unsupervised learning)

## Methods

### Data Preprocessing
- Removed ID and target variable
- Standardization using StandardScaler

### Models Used
- K-Means Clustering
- Agglomerative Clustering

### Model Selection
- Optimal clusters: k = 4 (Elbow + Silhouette method)

## Results
- K-Means outperformed Agglomerative clustering
- Silhouette Score: ~0.6 (K-Means)

## Key Insights
- Identified high-risk customers with ~62% default rate
- Low-risk segment with ~16% default rate
- Clear segmentation supports targeted strategies

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Business Impact
- Enables targeted credit risk strategies
- Supports personalized financial products
- Helps reduce default rates
