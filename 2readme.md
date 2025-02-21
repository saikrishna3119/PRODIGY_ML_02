# K-Means Clustering for Customer Segmentation

## Overview
This project implements the K-Means clustering algorithm to segment customers of a retail store based on their purchase history. The goal is to identify different customer groups to enable personalized marketing and enhance business strategies.

## Features
- Load and preprocess customer purchase data
- Apply K-Means clustering to segment customers
- Visualize customer clusters using scatter plots
- Optimize the number of clusters using the Elbow Method

## Requirements
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/kmeans-customer-clustering.git
   cd kmeans-customer-clustering
   ```
2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Prepare a dataset in CSV format with customer purchase data. Expected columns:
   - `CustomerID`
   - `Annual_Spend`
   - `Frequency`
   - `Recency`
   - `Monetary`

2. Run the clustering script:
   ```sh
   python kmeans_clustering.py
   ```
3. The script will generate cluster visualizations and print customer group insights.

## Tuning the Model
- Adjust the number of clusters (K) using the Elbow Method
- Experiment with different feature combinations
- Normalize data for better clustering performance

## Output
- Clustered customer groups
- Visual plots for interpretation
- Customer segment insights


