# Netflix-Recommendation-System
# 🎬 Netflix Recommendation System with Python

This project demonstrates how to build a **movie recommendation system** using the **Netflix Prize Dataset**. It utilizes collaborative filtering techniques and the Pearson correlation method to recommend movies based on user preferences.


##  Overview

Recommendation systems are used to predict the "rating" or "preference" a user would give to an item. 
This project demonstrates a **content-based** and **collaborative filtering** approach using real-world movie rating data provided by Netflix.

##  Dataset

- **combined_data_1.txt**: Contains user ratings for movies in the format:
- **movie_titles.csv**: Maps Movie_Id to movie title and release year.
Download from: https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data

##  How It Works

1. Load and clean the dataset
2. Filter movies and users based on activity
3. Create a user-movie rating matrix
4. Use Pearson correlation to find similar movies
5. Recommend top 10 similar movies for a given title

##  Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Surprise (for recommender models
