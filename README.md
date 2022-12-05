### Could we create a classifier that can distinguish between two music genres using Spotify API data?

Even if its easy to a human to classify correctly music genres, the large quantity of songs that are released every day makes it difficult and expensive to have people listening to and classifying them. Recomendation, for example, is one of the features that attracts people to use streaming apps like Spotify, so being able to their genres can be a success factor for streaming services.

In addition to the basic song metadata like release date, popularity and duration, the Spotify API can bring some information about the audio of the tracks. The "Audio Features" are metrics created by Spotify's audio analyzer software and relate to music theory stuff (like tempo, key and mode) and with how people perceive the song (like its energy, danceability and valence).

The objective of this project is, at first, to create a classifier that can distinguish tracks between brazilian rap and indie genres based on the Audio Features available in Spotify API.

The project is written in Python and uses the libraries spotipy, numpy, pandas, sklearn, matplotlib and seaborn. It addresses the following steps: ETL, EDA, Model Selection and Performance Evaluation.
