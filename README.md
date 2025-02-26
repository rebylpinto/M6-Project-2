# **<u>Project 2 - Spotify Listening History Analysis by Rebyl Peddity 🏫</u>**

###This repository contains an analysis of personal Spotify listening history data. The analysis explores various aspects of listening behavior, including top artists, tracks, and albums, as well as reasons for skipping and shuffling tracks.


| Column Name | Description |
| ----------- | ----------- |
| spotify_track_uri	 | Spotify URI that uniquely identifies each track in the form of "spotify:track:<base-62 string>" |
| ts | Timestamp indicating when the track stopped playing in UTC (Coordinated Universal Time) |
|platform | Platform used when streaming the track |
| ms_played | Number of milliseconds the stream was played |
| track_name | Name of the track|
| artist_name| 	Name of the artist|
| album_name | Name of the album|
|reason_start | Why the track started |
| reason_end |Why the track ended|
| shuffle	| TRUE or FALSE depending on if shuffle mode was used when playing the track |
| skipped| TRUE of FALSE depending on if the user skipped to the next song


##  Data

The data used for this analysis is stored in the `spotify_history.csv` file. 

## Analysis

The analysis is performed using Python with libraries such as pandas, seaborn, and matplotlib. 

The analysis includes:

* **Data cleaning and preprocessing:** Handling missing values and converting data types.
* **Descriptive statistics:** Exploring the distribution of listening times and identifying top artists, tracks, and albums.
* **Visualization:** Creating various plots to visualize listening patterns, including:
    * Scatter plots of listening time by time of day
    * Box plots of listening time by artist
    * Violin plots of skipped tracks by artist
    * Bar charts of top artists, tracks, and albums
    * Countplots of reasons for ending and skipping tracks
* **Analysis of skipping and shuffling behavior:** Investigating the reasons behind skipping and shuffling tracks.

## Findings

The analysis reveals insights such as:

* The most frequently played artist, track, and album.
* The average listening time and its distribution across artists and tracks.
* The most common reasons for ending and skipping tracks.
* The frequency and reasons for shuffling tracks.

