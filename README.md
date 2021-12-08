# Predicting the Popularity of a Song Based on Spotify Metrics

## Description of the data 

### Source of data
https://www.kaggle.com/sashankpillai/spotify-top-200-charts-20202021

Number of observations: 1517

### Response variable

Popularity: The popularity of the track. The value will be between 0 and 100, with 100 being the most popular.

### Explanatory variables (9 total)

Descriptions below are taken directly from Spotify developer web API (https://developer.spotify.com/documentation/web-api/reference/#object-audiofeaturesobject). They can be found under the AudioFeaturesObject section.

Danceability: Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.

Acousticness: A measure from 0.0 to 1.0 of whether the track is acoustic.

Energy: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy.

Instrumentalness: Predicts whether a track contains no vocals. The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content.

Liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live.

Loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track. Values typical range between -60 and 0 db.

Speechiness: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value.

Tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.

Valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).


## Precise description of the questions

Using various features/descriptors of songs, how can we best predict the popularity of the song?

## Why this question

We love music, and we love data science, and we love listening to music while we’re working with datasets. So, understanding how songs become popular is super interesting to us; figuring out how things like tempo, valence or loudness affect how popular a song can become is a neat goal to have. Spotify's developer web api gives us measurable data on features of a song's audio, as well as how popular a song is given its streaming counts. This gives us the perfect dataset to answer our question.

## Reading list 

An Analysis of Spotify’s Top 200 Worldwide Daily Song Rankings in 2017 by Nathaniel Lao 
  http://natelao.com/SpotifyAnalysis/SpotifyAnalysis.html
  
Spotify Developer Web API Reference
  https://developer.spotify.com/documentation/web-api/reference/
