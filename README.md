## Spotify Song Recommendation System

## Description
This project uses Python to create a Spotify recommendation system by comparing cosine similarity of an input song and all tracks found in this [1.2+ million song dataset](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs?reso=) from Kaggle. Clustering, an unsupervised machine learning algorithm, is utilized to reduce the processing time of this system by only comparing the input song to other songs within its cluster. I was inspired to create this to find new songs based on a song I like that is independent from artist or genre, and instead base recommendations on song composition metrics provided by Spotify's API. Some of these metrics include danceability, energy, valence, etc. that may be able to quantify the overall "vibe" of a song. This was a fun project because I got to explore some of Spotify's open developer tools like Spotify for Developers, Spotify API, and the Python package 'spotipy', and listen to some fun new songs that I may not have found otherwise.

Things you need before you start:
- Download [Spotify 1.2m+ Songs](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs?reso=) dataset from Kaggle
- A Spotify account (free or premium)
- Sign up for [Spotify For Developers](https://developer.spotify.com/discover/) with your personal Spotify account, create a new app, and retrieve your client id and secret client id

I intend to expand on this project a bit more. Here are some of the things I have been thinking about adding/improving on:
- Figure out how to incorporate the app I made on Spotify for Developers
- Create a more interactive way to get recommendations
make classes for song and playlist so that I can call methods like get_name(), get_cluster(), play_30_sec(), get_URL(), etc
- Create a playlist from recommendations
- Input multiple songs
- Try different types of differences (cosine is often used for recommendations, but more research should be done)
- Features importances: what features are most important for the overall "vibe"?
- More personalized recommendations?
