# Spotify Album Analysis 

This Python application allows users to analyze audio features of tracks from specified albums using the Spotify API. It provides insights into various aspects of music, including danceability, energy, valence, tempo, acousticness, and instrumentalness.

## Features

- Retrieve tracks from a specified album using the Spotify API.
- Extract audio features such as danceability, energy, valence, tempo, acousticness, and instrumentalness for each track.
- Visualize the audio features of tracks within the album using scatterplots for easy comparison.
- Annotate scatterplots with corresponding audio feature values for better understanding.

## How to Use

1. Clone the repository to your local machine:

```
git clone https://github.com/your-username/music-analysis-app.git
```

2. Install the required libraries:

```
pip install -r requirements.txt
```

3. Replace `'YOUR_CLIENT_ID'` and `'YOUR_CLIENT_SECRET'` with your actual Spotify API credentials in the code.

4. Run the `music_analysis.py` script:

```
python spotify-album-analysis.py
```

5. Enter the name of the album you want to analyze when prompted.

6. View the generated scatterplots comparing audio features of tracks within the album.

## Requirements

- Python 3.x
- spotipy
- pandas
- seaborn
- matplotlib
