# Movie Recommendation System

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-0.89.0-brightgreen)

Welcome to the Movie Recommendation System project, a sophisticated machine learning application that leverages the power of Python libraries to provide tailored movie recommendations. This project utilizes libraries such as Pandas, NumPy, Streamlit, Pickle, and Ast to create an efficient recommendation engine through text vectorization. By employing this advanced concept, we have developed an index that facilitates the generation of up to five movie recommendations for any film in the database.

## Overview

The primary goal of this project is to provide personalized movie recommendations to users based on their preferences and the characteristics of the movies. This is achieved through a multi-step process involving data preprocessing, text vectorization, and recommendation generation.

## Project Workflow

1. **Data Collection and Preprocessing:**
   - We start by gathering a comprehensive dataset of movies, including attributes such as title, genre, and description.
   - The dataset is then cleaned and preprocessed to remove duplicates, handle missing values, and ensure data consistency.
   - The dataset used is: ![kaggle dataset link](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

2. **Text Vectorization:**
   - The descriptions of movies are processed using advanced text vectorization techniques.
   - This process involves converting text into numerical representations that capture the semantic meaning of the words.

3. **Recommendation Generation:**
   - Once the text vectorization is complete, we create a similarity matrix based on the vectorized descriptions of movies.
   - This matrix allows us to measure the similarity between different movies in the dataset.
   - Given a specific movie, we can identify similar movies based on the calculated similarities.

4. **Streamlit User Interface:**
   - To make the recommendation system accessible, we develop a user-friendly Streamlit application.
   - Users can enter the name of a movie they like, and the application will provide a list of recommended movies based on the provided input.
