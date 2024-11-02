# Item-Based Collaborative Filtering Recommendation System
This repository contains an item-based collaborative filtering recommendation system with a front-end interface built using Streamlit and a REST API powered by FastAPI. The system generates personalized recommendations by analyzing similarities between items based on user interactions.

## Project Overview
The item-based collaborative filtering approach recommends items to users by analyzing relationships between items they have previously interacted with. This project leverages collaborative filtering to compute similarity between items and provide recommendations that align with user preferences.

## Key Features
- Item Similarity Calculation: Calculates item similarities using various metrics like cosine similarity and Pearson correlation.
- FastAPI Backend: Provides a REST API for model inference and easy integration.
- Streamlit Frontend: Interactive interface for users to explore recommendations.
- Scalable Design: Supports handling large datasets efficiently.
# Dataset
- Source: Test the system with datasets like <a href="https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset">MovieLens</a> or any user-item interaction data.
## Methodology
- Data Preprocessing: Load and preprocess user-item interaction data.
- Similarity Calculation: Compute item-item similarity based on user ratings using metrics like cosine similarity.
- Recommendation Generation: Recommend items similar to those the user has interacted with
## Streamlit Interface
The Streamlit app provides an interactive frontend to view recommendations.
```bash
streamlit run app.py
