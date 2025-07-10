# netflix-clustering-analysis_guvi
# Netflix Clustering Analysis

This project applies unsupervised learning techniques to cluster Netflix movies and TV shows based on metadata like genres, duration, and release year. The objective is to uncover meaningful content groupings for recommendations and content analysis.

## Overview

- Cleaned and preprocessed the dataset
- Engineered features: duration in minutes, content age, genre encoding
- Applied clustering algorithms: KMeans, DBSCAN, and Hierarchical
- Visualized clusters using PCA and dendrograms
- Evaluated cluster quality using Silhouette Score and Davies-Bouldin Index

## Cluster Highlights

- Cluster 0: International crime and drama TV shows
- Cluster 1: Kids content and animated series
- Cluster 2: Classic comedy, action, and global cinema
- Cluster 3: Documentaries and popular global dramas

## Files

- `Netflix_Clustering_Completed.ipynb`: Full project notebook
- `netflix_clustered.csv`: Final dataset with cluster labels
- `netflix_clustered.xlsx`: Excel version of the dataset
- `README.md`: Project summary and structure

## Tools Used

Python, Pandas, Scikit-learn, Matplotlib, Seaborn
