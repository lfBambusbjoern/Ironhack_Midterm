## Spotify-EDA: "Is it going to be a hit?"

**Step 1:** <br>
a) Merge all data points I currently have (via [kaggle](https://www.kaggle.com/theoverman/the-spotify-hit-predictor-dataset), [spotify api](https://developer.spotify.com/documentation/web-api/), ...) into one dataset.
Other datasets: [link1](https://www.kaggle.com/iamsumat/spotify-top-2000s-mega-dataset), [link2](https://www.kaggle.com/leonardopena/top-spotify-songs-from-20102019-by-year), ...<br>
b) Clean and prepare the new EDA dataset.

**Step 2:**<br>
a) Analyze how the priority of musical elements for "hit-songs" (needs to be defined more specific in b) changed through the time by using the API's Parameters that classify songs (such as their acousticness, energy, bpm, ...). <br>
b) Compare those to standard parameters that would be relevant for a classification of the popularity of those songs.

**Step 3:**<br>
a) Create a function that let's a user insert own playlist / song links (both necessary?) via Spotify Links (is there a way to slice the link into different pieces to recreate the correct link on request?). <br>
b) Create a ML concept that checks, how well the chosen songs might perform while using the analysis from step 2 as evaluation.
