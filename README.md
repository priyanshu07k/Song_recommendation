
# Music Recommender Systems

This repository contains two different approaches to music recommendation: a k-Nearest Neighbors (k-NN) based system and a content-based filtering system. Both notebooks rely on the `Song_data.csv` file for input data.

## Project Files

1. **KNN Music Recommender (`KNN_music_recommender.ipynb`)**
   - Implements a k-NN based recommendation system.
   - Recommends songs to a user based on the listening habits of similar users.

2. **Content-Based Music Recommender (`Content_based_recommendor.ipynb`)**
   - Implements a content-based recommendation system.
   - Recommends songs based on textual similarity in song descriptions.

## Data

Both notebooks require a CSV file named `Song_data.csv`, which should contain the following columns:
- `user_id`: Unique identifier for each user.
- `song_id`: Unique identifier for each song.
- `frequency`: The number of times a user has listened to a song.
- `song`: The title of the song (used in content-based recommender).
- `text`: Description or lyrics of the song (used in content-based recommender).

## Usage

- Open the desired Jupyter notebook.
- Ensure that `Song_data.csv` is in the same directory as the notebook.
- Run all cells to see the recommendation system in action.

## Dependencies

Both notebooks use the following Python libraries:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

Ensure these libraries are installed in your environment before running the notebooks.
