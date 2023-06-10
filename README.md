# 🎬 RecommendationSystem-movie 🎥

## 🌐 Overview

"RecommendationSystem-movie" is a project for building a movie recommendation system, similar to Netflix. 🍿 It uses various techniques, including Knowledge/Rank based recommendation, Similarity-Based Collaborative filtering, and Matrix Factorization Based Collaborative Filtering.

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/LVH-Tony/RecommendationSystem-movie.git
```

## 📋 Prerequisites

You need:

- Python 3.6 or later 🐍
- Jupyter Notebook 📓
- Pandas 🐼
- Numpy ➕
- Matplotlib 📊
- Seaborn 📈
- Scikit-learn 🤖
- Surprise library 😲

## 📊 Dataset

The project uses a ratings dataset (`data.csv`) with attributes: userId, movieId, rating, timestamp.

## 🛠️ Usage

Open `Movie-Recommendation-System.ipynb` in Jupyter Notebook and run the cells.

## 🎯 Recommendation Systems

The project builds three types of recommendation systems:

1. **Knowledge/Rank based recommendation system**: Recommends movies based on popularity or critical acclaim.
2. **Similarity-Based Collaborative filtering**: Recommends movies that similar users have liked.
3. **Matrix Factorization Based Collaborative Filtering**: Decomposes the user-item interaction matrix into the product of two lower dimensionality rectangular matrices.

## 📈 Results

The recommendation system was evaluated using RMSE and MAE. The system was also tested with different hyperparameters to optimize the performance.

1. **SVD Based Collaborative Filtering**: RMSE for the optimized model was 0.8957.
2. **Item Based Collaborative Filtering**: The optimized model predicted ratings for movies that a user has not interacted with before.
3. **Matrix Factorization Using SVD**: The RMSE for the optimized model was 0.9571.
4. **Similarity Based Recommendation System**: The system was able to recommend top 5 movies for a user.

## 📝 Conclusion

The recommendation system can predict movie ratings with reasonable accuracy and recommend top movies for users. The system was optimized using various techniques and evaluated using different metrics.
