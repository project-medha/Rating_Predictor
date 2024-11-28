# Movie Rating Predictor using KNN 
This repository contains a Python-based implementation of a Movie Recommender System using the K-Nearest Neighbors (KNN) algorithm. The system analyzes a dataset of movie ratings and features (like genres and popularity) to recommend similar movies based on user preferences or a selected movie.

# Features
- Data Loading and Preprocessing:
  -  Reads user ratings and movie information from provided datasets.
  -  Normalizes popularity scores to create a standardized metric.
  -  Constructs a movie dictionary containing metadata such as genres, popularity, and average ratings.
- Similarity Calculator
  - Uses a custom distance metric combining:
    - Cosine similarity for genres.
    - Absolute difference for popularity scores
  - Recommendation Engine
    - Identifies the top K nearest neighnours (movies) for a given movie using KNN
    - Outputs the average ratings of recommended movies for comparison.
