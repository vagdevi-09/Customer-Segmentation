# Customer Segmentation Analysis Using K-Means Clustering

## Project Overview

This project focuses on customer segmentation using the K-Means Clustering algorithm. The objective is to group customers into distinct segments based on their purchasing behavior and income characteristics. Customer segmentation helps businesses identify target audiences, improve marketing strategies, and enhance customer retention.

## Dataset

The dataset contains customer information, including:

* Annual Income
* Spending Score
* Purchase Frequency

These features are used to identify customer groups with similar behaviors.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Workflow

### 1. Data Loading

The dataset is loaded using Pandas and inspected for data quality.

### 2. Data Preprocessing

* Handling missing values (if any)
* Selecting relevant features
* Preparing data for clustering

### 3. Exploratory Data Analysis (EDA)

Basic statistical analysis is performed to understand customer behavior and feature distributions.

### 4. K-Means Clustering

The K-Means algorithm is applied with:

```python
KMeans(n_clusters=5, random_state=42)
```

Five customer segments are created based on customer characteristics.

### 5. Cluster Visualization

Customer segments are visualized using a scatter plot:

* X-axis: Annual Income
* Y-axis: Spending Score
* Color: Cluster Assignment

### 6. Cluster Analysis

Average values for each cluster are calculated to understand the characteristics of different customer groups.

```python
cluster_analysis = df.groupby("Cluster").mean(numeric_only=True)
```

## Results

The model successfully divides customers into 5 distinct clusters. Each cluster represents a unique customer segment with different income levels, spending patterns, and purchase frequencies.

### Potential Customer Segments

* High Income, High Spending Customers
* High Income, Low Spending Customers
* Medium Income, Medium Spending Customers
* Low Income, High Spending Customers
* Low Income, Low Spending Customers

## Business Applications

* Personalized Marketing Campaigns
* Customer Retention Strategies
* Product Recommendations
* Loyalty Programs
* Revenue Growth Planning

## Visualizations

The project includes:

* Customer Segmentation Scatter Plot
* Cluster-wise Performance Analysis
* Cluster Mean Comparison

## Key Insights

* Customers exhibit distinct purchasing behaviors.
* High-spending customers can be targeted for premium products.
* Low-spending customers can be engaged through promotional campaigns.
* Segment-based marketing can improve overall business performance.

## Future Enhancements

* Use the Elbow Method to determine the optimal number of clusters.
* Implement advanced clustering algorithms such as DBSCAN or Hierarchical Clustering.
* Develop an interactive Power BI dashboard for business users.
* Add customer demographic features for more accurate segmentation.

## Author

**Vagdevi Bodala**

Data Analytics Project – Customer Segmentation Analysis using K-Means Clustering.
