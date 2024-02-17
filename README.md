
# Recommendation System using Content-Based Filtering and Collaborative Filtering

This recommendation system is implemented using both content-based filtering and collaborative filtering techniques. It provides personalized recommendations to users based on their preferences and past interactions with items.

## Introduction
The recommendation system is designed to analyze user-item interactions and item features to generate personalized recommendations. It utilizes text-based features such as tags and hashtags to perform content-based filtering, as well as user-item interaction data for collaborative filtering.

## Features
- **Content-Based Filtering**: Analyzes item features such as tags and hashtags to recommend similar items to users based on their preferences.
- **Collaborative Filtering**: Utilizes user-item interaction data to identify patterns in user behavior and recommend items that similar users have interacted with.
- **Data Preprocessing**: Cleans and preprocesses data to handle missing values, remove non-ASCII characters, convert text to lowercase, and remove punctuation.
- **TF-IDF Vectorization**: Converts text features into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
- **Cosine Similarity**: Calculates the cosine similarity between item vectors to measure the similarity between items.
- **Nearest Neighbors (KNN) Model**: Uses KNN algorithm to find the nearest neighbors of an item based on its feature vector.
- **Recommendation Generation**: Generates top-k recommendations for a given item using both content-based and collaborative filtering approaches.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- NLTK
- matplotlib
- seaborn
- Pillow

## Execution
1. Open .ipynb in the Jupyter notebook interface.
2. In the 'Cell' dropdown menu, select 'Run all below' option to run the notebook.

## Functionality
- **Preprocessing**: Preprocesses data to handle missing values, clean text features, and combine text features.
- **Content-Based Filtering**: Analyzes item features to recommend similar items based on their features.
- **Collaborative Filtering**: Utilizes user-item interaction data to recommend items that similar users have interacted with.
- **Recommendation Generation**: Generates personalized recommendations for users based on their preferences and past interactions.

## Troubleshooting
If the solution does not display, check the following:
1. Make sure all the libraries are installed and imported.
