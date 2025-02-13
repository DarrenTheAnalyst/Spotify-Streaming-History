# Spotify-Streaming-History
Custom SQL querying to tackle the recommended analysis of the Spotify Streaming History dataset from Maven Analytics.

My approach:

1) Explore the CSV file in Excel by filtering columns to ask questions about the data.
2) Bring the CSV file into DB Browser and ensure data types.
3) Query questions from 1).
4) Query the recommended analysis from Maven.

Questions I queried:

- Are spotify_track_uni distinct?
- Is it possible to calculate the start time for the field ts?
- Does it make sense to change the data type for ms_played from Integer to Real? Why?
- Does it make sense to treat NULL in the fields reason_start and reason_end as 'unknown'?

Maven recommended analysis:

1) Which artist did they listen to the most this year? Is it the same as last year?
2) Which songs have they played the most? How often do they skip them?
3) What time of the day do they typically listen to music?
4) How often do they explore new artists versus replaying favourites? 
