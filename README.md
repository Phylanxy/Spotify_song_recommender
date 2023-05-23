# Spotify_song_recommender
This is a short project to build a song recommender based on numerical features of songs obtained from the Spotify API

## Structure
### Model creation
In TrainingTheModel, the recommendation model is trained on about 22k songs that are pulled from playlists on Spotify aiming for a balanced selection of songs in order to get the best recommendations. 

### Recommender
Actual recommendation based on user input, either returns a song of the hot 100 or from the dataframe the model was trained on.
