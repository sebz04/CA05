# CA05
Computer Assignment 05 kNN Recommender

This project builds a movie recommendation system using the k-Nearest Neighbors (kNN) algorithm.

Given a dataset of movies with features like IMDB rating and genre indicators, the model identifies the 5 most similar movies to a selected query movie ("The Post").

This is a similarity-based problem.

#Steps

## 1.Load Data
Dataset is imported from a GitHub CSV file
Contains movie features and metadata

## 2.Data Exploration
Checked dataset shape, structure, and summary statistics
Confirmed all features are numeric

## 3.Data Cleaning
Removed non-relevant columns:
- Movie ID
- Movie Name
- Label
Standardized features using StandardScaler

## 4.Model Building
Used NearestNeighbors from sklearn
Applied Euclidean distance
Configured to return 5 nearest neighbors

## 5.Query Input
Created a feature vector representing "The Post"
Scaled using the same transformation as training data

## 6.Recommendations
Model calculates distances
Returns the 5 most similar movies

#Key Concepts
- k-Nearest Neighbors (kNN): Finds similar items based on distance
- Feature Scaling: Ensures fair comparison across variables
- Euclidean Distance: Measures similarity between movies

#How to Run...
Open the notebook (CA05.ipynb) in Jupyter Notebook or Google Colab --> Run all cells in order --> View the recommended movies output at the end

