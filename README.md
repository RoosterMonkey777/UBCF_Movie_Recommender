# UBCF_Movie_Recommender

# User-Based Collaborative Filtering Recommender System

This project implements a movie recommendation engine using **User-Based Collaborative Filtering** on the [Kaggle Movies Dataset](https://www.kaggle.com/). It filters, preprocesses, and analyzes user ratings to recommend movies based on the preferences of similar users.

## Project Structure

- `UserBasedCollaborativeFilteringRecommender.ipynb`: Main notebook with full implementation.
- `ratings.csv`, `movies_metadata.csv`, `credits.csv`: Input datasets.
- `distribution_predicted_ratings.png`: Visual showing distribution of predicted ratings.
- `report.tex`: Final academic report written in LaTeX (optional).

## Features

- Data cleaning and preprocessing
- Construction of user-item matrix
- Cosine similarity to identify user neighbors
- Predicted ratings using weighted average of neighbors
- Top-N recommendations per user
- Evaluation metrics:
  - RMSE
  - Precision@K, Recall@K, NDCG@K
- Visualizations of rating distribution

## How to Run

1. Clone the repo
2. Place dataset CSV files in the root directory
3. Run the notebook step by step

## Requirements

- Python 3.x
- pandas, numpy, sklearn, matplotlib, seaborn

Install dependencies:
```bash
pip install -r requirements.txt
