# Movie-Recommendation-System

## Overview
This repository contains a Movie Recommendation System built using Content-Based Filtering. The system recommends movies to users based on the similarity of movie features, such as genres, directors, and plot descriptions. Content-based filtering focuses on suggesting items that are similar to those the user has liked in the past.

## Features

Content-Based Filtering: Recommends movies similar to those a user has liked, based on movie metadata. User Input: Allows users to input their favorite movie(s) to receive recommendations. Similarity Metrics: Utilizes cosine similarity to measure the similarity between movies.

## Dataset

The system uses a movie dataset containing information such as: Movie titles Genres Directors Cast

## Installation

To run this project locally, follow these steps:
1. Clone the repository:
Copy code git clone https://github.com/UmeshGurawalia/Movie-Recommendation-System

2. Install the required dependencies: Ensure you have Python installed. Then install the required Python packages using pip: Copy code pip install -r requirements.txt The requirements.txt file should include packages such as pandas, numpy, scikit-learn, and nltk (for text processing).

3. Download the dataset

## How It Works
Data Preprocessing:

The dataset is cleaned and relevant features (e.g., genres, plot summaries) are extracted. Text data is transformed into a format suitable for machine learning, typically using TF-IDF (Term Frequency-Inverse Document Frequency).

Model Training:

The content-based filtering model calculates the similarity between movies based on the extracted features. Cosine similarity is commonly used to measure the similarity between movie feature vectors.

Generating Recommendations:

When a user inputs a movie title, the system retrieves the corresponding feature vector and computes the similarity with all other movies in the dataset. The top N most similar movies are recommended to the user.

## Point to note
similarity.pkl movie_list.pkl

This two are large file so download manully after creating the model from Movie_Recommendation_System.ipynb
