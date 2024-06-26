# NLP Content-Based Movie Recommendations

## Introduction

This project implements content-based movie recommendations using Natural Language Processing (NLP) techniques such as Bag of Words (BoW), Term Frequency-Inverse Document Frequency (TF-IDF), and Cosine Similarity score. 
The aim is to recommend movies similar to a given movie based on their textual descriptions.

## Features

- Utilizes movie descriptions to create a numerical representation using BoW and TF-IDF.
- Calculates the similarity between movies using Cosine Similarity.
- Provides recommendations based on the similarity scores.

## Libraries
- Pandas
- Numpy
- Seaborn, Matplotlib
- Gensim
## Usage
query_recommendation(movie_title, number_of_recommendations)

## Dataset
The dataset used in this project should contain 12 columns. 'keywords' is the main column with all the necessary key words.
Ensure that the descriptions are cleaned and preprocessed before using them for recommendations.

## Contributing
Contributions are welcome! If you have any ideas for improvement or new features, feel free to open an issue or submit a pull request.
