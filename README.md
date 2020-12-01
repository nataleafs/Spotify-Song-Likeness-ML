# Do You Like This Song?
 ## Introduction 
This is a Machine Learning (ML) project predicting Spotify song likeness, whether a user will like or dislike a particular song in one of his Spotify playlists. Worked on the two datasets using ML models: Logistic Regression, K-Nearest Neighbours (KNN) and XGBoost, examining the precision of these algorithms in predicting whether a song will be liked or disliked by a user. 

## Predicting Songs: 
### Data 
The datasets are collections of song data from Spotipy, a Python library for the Spotify web API. It consists of 100 songs each from two Spotify playlists. I was able to access artist names, album names, track name, track ID and audio features such as danceability, energy, key, loudness, mode speechiness, instrumentalness, liveness, valence, tempo, duration of songs in milliseconds and time signature. 

## Exploratory Data Analysis and Insights
- Coldplay had one of the highest number of songs in the playlist.
- The louder the song, the more energy is generated. 
- The playlist comprises of songs by many different artists.

Limitations: 
- The datasets lacked Popularity and Genre columns. 

## Methodological process and results
- Classification algorithms Logistic Regression and K-nearest Neighbours (KNN) were used as the nature of the project involved classifying songs as liked or disliked respectively. 
- The XGBoost algorithm was used to improve the performance of the classification models used.
- Logistic Regression algorithm generated a precision value of 0.64 in predicting song likeness.
- K-nearest Neighbours algorithm generated a precision value of 0.71 in predicting song likeness.
- XGBoost algorithm generated a precision value of 0.91 in predicting song likeness.

## Conclusion 
The datasets of 100 songs each makes it difficult for more complex ML projects to be done. The lack of Popularity and Genre columns in the datasets also make it impossible for song and genre popularity related ML projects to be done. 


## References 
This list is a non-exhaustive list of the main sources of information used in working on this project.

- https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/
- https://machinelearningknowledge.ai/mini-ml-project-predicting-song-likeness-from-spotify-playlist/
- https://www.kaggle.com/nxrprime/spotify-song-eda
- https://www.kaggle.com/cnic92/spotify-songs-attributes-eda
