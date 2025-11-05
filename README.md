# TrackVibes
CSE 475 Milestone Project

# TrackVibes

TrackVibes sorts songs into playlists based on their audio features. The goal is to take a song I like, look at its musical qualities, and suggest which playlist it fits into.

## Dataset
I am using the Spotify Tracks Dataset. It includes:
- energy
- danceability
- valence
- acousticness
- liveness
- tempo
- key
- mode
- time_signature
- explicitness

These features help describe the feel and mood of a song.

## What This Project Does
1. Load and preview the dataset.
2. Explore feature patterns and distributions.
3. Clean the data and handle missing values.
4. Prepare features for modeling.
5. Train a model that predicts a playlist label.
6. Evaluate how well the model performs.

## Goal
The model should learn how I group songs by vibe. It will take the audio features of a new song and suggest the playlist it belongs to. This supports building or sorting playlists in a simple and repeatable way.

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

