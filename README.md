# Movie Recommendation System

This project implements a collaborative filtering recommendation system to predict movie ratings and recommend movies to users.

## Dataset

The dataset consists of two files:
- `ratings.csv`: Contains user ratings for movies.
- `movies.csv`: Contains metadata about movies.

## Methodology

1. **Data Preparation**: Merge the ratings and movies datasets.
2. **Normalize Ratings**: Normalize the user-item matrix.
3. **Calculate Similarity**: Compute item similarity using Pearson correlation.
4. **Make Predictions**: Predict ratings for movies that a user has not rated.