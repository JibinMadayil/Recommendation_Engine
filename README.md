# Recommendation Engine


Anime Recommendation System
This repository contains an analysis and implementation of an anime recommendation system using collaborative filtering and content-based filtering techniques. The analysis involves data preprocessing, visualization of anime data, creation of recommendation models, and building a user-friendly recommendation interface.

Introduction
The goal of this project is to develop a recommendation system that suggests anime titles to users based on their preferences. Two main techniques are employed: collaborative filtering, which recommends items based on user behavior and preferences, and content-based filtering, which recommends items similar to those the user has shown interest in.


Data
The dataset used in this analysis includes information about anime and ratings.

Analysis Steps
Data Loading and Preprocessing: Anime and rating data are loaded, merged, and cleaned. Duplicate and missing values are handled.

Exploratory Data Analysis (EDA): Basic statistics and visualizations are used to understand the distribution of anime features, user ratings, and more.

Collaborative Filtering: User-item interactions are analyzed, and a pivot table is created for user-item ratings. Nearest Neighbors algorithm is used to find similar items.

Content-Based Filtering: The TF-IDF vectorization technique is applied to genre data to recommend similar anime.

Results
The analysis provides insights into user preferences, anime popularity, and correlations between anime features. Collaborative filtering and content-based filtering are used to generate recommendations.

Recommendation Interface
A user-friendly recommendation interface is developed, allowing users to input anime titles and receive recommendations based on their preferences.

Conclusion
The recommendation system demonstrates two powerful techniques for suggesting anime to users: collaborative filtering and content-based filtering. The interface provides an intuitive way for users to discover new anime titles based on their interests.
