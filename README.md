# **Movie Recommendation System**
This project implements a movie recommendation system using collaborative filtering techniques with deep learning. It uses a neural network model to predict user ratings for movies and recommends top movies based on the predictions. The dataset used is the MovieLens 100k dataset.

**Requirements**

pip install pandas numpy scikit-learn tensorflow matplotlib seaborn

**Dataset**

The dataset used in this project is the MovieLens 100k dataset which is available on GroupLens. The dataset contains 100,000 movie ratings from 943 users on 1682 movies.
1. User ID: The ID of the user who rated the movie.
2. Movie ID: The ID of the movie.
3. Rating: The rating given to the movie (on a scale from 1 to 5).
4. Timestamp: The time the rating was given
The code automatically downloads and unzips the dataset.

**Features**

1. Data Preprocessing: Loads and cleans the data by removing irrelevant columns and encoding user and movie IDs.
2. Exploratory Data Analysis: Visualized the distribution of ratings, user IDs, and movie IDs and creates scatter plot and bar plot to analyze user-movie interactions.
3. Collaborative Filtering Model: Used neural networks with embedding layers to learn user and movie preferences.
4. Movie Recommendations: The model predicts ratings for all movies for a given user and recommends the top N movies based on the predicted ratings.
5. Model Evaluation: The model's performance is evaluated using Mean Squared Error (MSE) to measure prediction accuracy.
6. Visualizations: Generated histogram and scatter plot to explore and visualize the data.
