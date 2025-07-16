# Matplotlib Fundamentals

These notebooks were developed as part of the AI & Data Specialist program with Develhope, to apply and deepen the skills acquired during the course.

## Project Structure

This project is composed of the following files:

### `cleaner.py`

This script contains functions for cleaning the dataset. It defines the feature sets to be used in the analysis and provides a function to select only those features from the raw dataset, as well as stripping any leading/trailing whitespace from column names.

### `outlier_detection.ipynb`

This notebook focuses on identifying and analyzing outliers within the dataset. It employs various data visualization techniques, such as correlation heatmaps and violin plots, to explore data distributions. Outlier detection is carried out using the standard deviation method, and the results are visualized to illustrate the proportion of outliers.

### `plots.ipynb`

This notebook is dedicated to data visualization and advanced analysis techniques. Key topics include:

- **Data Visualization**: Creation of plots to visualize normal distributions with varying variances, histograms with quartiles to understand data distributions, and visualizations of normalized data.
- **Clustering with DBSCAN**: Use of K-distance graphs to determine the optimal parameters for the DBSCAN clustering algorithm and subsequent application to identify clusters in the data.
- **Outlier Detection with LOF**: Implementation of the Local Outlier Factor (LOF) method to detect anomalies, including the visualization of anomaly scores to distinguish outliers from inliers.