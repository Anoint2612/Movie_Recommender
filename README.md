# Movie Recommender System

This project is a web-based Movie Recommender System developed using Streamlit. It allows users to get personalized movie recommendations based on a selected movie. The recommendation engine uses a similarity matrix and dynamically fetches movie posters from the TMDB API.

## Features

- **Movie Recommendations**: Provides a list of 5 similar movies based on the selected movie.
- **Dynamic Poster Fetching**: Retrieves posters using the TMDB API.
- **Interactive UI**: Simple, easy-to-use interface built with Streamlit.

## How It Works

1. **Select a Movie**: Choose a movie from the dropdown menu.
2. **Show Recommendations**: The app displays 5 similar movies along with their posters.
3. **Similarity Calculation**: The system uses a precomputed similarity matrix to find the closest matches.

## Project Structure

```plaintext
.
├── app.py                 # Main application file
├── movies.pkl             # Precomputed movies data
├── similarity.pkl         # Precomputed similarity matrix
├── M_recommender.ipynb     # Jupyter notebook for data preprocessing and model development
├── README.md              # Project documentation

'
'''
