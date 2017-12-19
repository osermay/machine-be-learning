# Project: Predicting Happiness of Songs
Final project for NYU's Intro to Machine Learning
by **Kristin Moser and Shayaan Saiyed**

Open ML_final_km3322_sas1122.ipynb in Jupyter

In this demo, we illustrate how to use Spotify API audio features data to determine the happiness of a song. The steps we took to do so:
* Process API data to retrieve audio features for around 1000 songs
* Perform multiple linear regression
* Use K-fold cross validation to choose the best model

We used Spotify's API as well as the Spotipy library:
* [Spotify API](https://developer.spotify.com/web-api/)
* [Spotipy](http://spotipy.readthedocs.io/en/latest/) 

We drew inspiration from several other projects that have been done.
> This [project](https://github.com/juandes/spotify-audio-features-data-experiment) used Spotify track's audio features (like us) to determine whether or not a user's music taste was boring. This was interesting, however, a self-defined feature set. The creator decided what values of the audio features qualified it as boring. In this [article](https://towardsdatascience.com/is-my-spotify-music-boring-an-analysis-involving-music-data-and-machine-learning-47550ae931de) they wrote about their process.

>This [project](https://devpost.com/software/partify-k94hpq) used Spotify track's audio features to reccommend songs to a ongoing party playlist. The user's favorited songs along with a selected mood fromt the user helps the app search for songs and creates a playlist from them. This application uses SVM to classify songs.

