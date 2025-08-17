# Movie-Recommender-System
This project implements a Movie Recommendation System using Singular Value Decomposition (SVD), a popular collaborative filtering technique to predict user ratings for movies based on past behavior and preferences.

 **About the Dataset**
This data set consists of:
* 100,000 ratings (1-5) from 943 users on 1682 movies.
* Each user has rated at least 20 movies.
* Simple demographic info for the users (age, gender, occupation, zip)

[Dataset Link](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset)

Project Overview
Objective: Accurately predict how users would rate unseen movies and recommend those most likely to match their tastes.

Approach: Collaborative Filtering using SVD, which leverages patterns in the existing user-movie ratings matrix to estimate preferences.


Key Features
Data pre-processing and visualization to explore ratings and movie genres.

SVD-based algorithm implementation using scikit-surprise.

Prediction of user ratings for movies not previously rated.

Option to recommend top movies tailored to each user’s preference profile.
