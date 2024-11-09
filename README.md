Hello! This is my Exploratory Data Analysis about a dataset containing information about popular tracks on Most Streamed Spotify Songs 2023. 

# Guide Questions
## Overview of Data Set
### How many rows and columns does the dataset contain?
using the code data.shape, the dataset contains 953 rows and 24 columns.

### What are the data types of each column? Are there any missing values?
There are two data types each column has. The int and the object. There are also many missing values so what i did is i remove it using the dropna. at the end of the code, We can notice thst The datatype object became float since I converted them and needed the values of stream and tracks. 

## Basic Descriptive Statistics

### What are the mean, median, and standard deviation of the streams column?
- I calculated the mean and the answer is 514137424.93907565. While the median is 290530915.0 and standard deviation is 566856949.0388832.

### What is the distribution of released_year and artist_count? Are there any noticeable trends or outliers?
- In my code, you can see two plots there. As we can see in the first graph, 2020 is the most released year. 

## Top Performers

### Which track has the highest number of streams? Display the top 5 most streamed tracks.

- Blinding Lights is the most highest number of streams. You can see in my code the top 5 most streamed tracks. I also used the data sort values to sort then in descending order.
  
### Who are the top 5 most frequent artists based on the number of tracks in the dataset?
-The top 5 most frequent artist is taylor swift, The weekend, Bad bunny, Sza and Harry Styles. 

 ## Temporal Trends

### Analyze the trends in the number of tracks released over time. Plot the number of tracks released per year.
- The plot is in my code. As I analyze the trends, 2022 is the most trends that released over time. 2023 is the second trend.
  
### Does the number of tracks released per month follow any noticeable patterns? Which month sees the most releases?
- January and May are the most the number of tracks release. I notice thst every trend that release, the next month will be the least.
  
## Genre and Music Characteristics

### Examine the correlation between streams and musical attributes like bpm, danceability_%, and energy_%. Which attributes seem to influence streams the most?
- Liveness is the most influence in streams. next is instrumentalness. As I examine the correlation, The Musical attribute has influence in streams.
  
### Is there a correlation between danceability_% and energy_%? How about valence_% and acousticness_%?
- danceability and energy has more correlation than the valence and acousticness. I thought of that because the result in valence and acousticness is negative while the other one is positive.
  
## Platform Popularity

### How do the numbers of tracks in spotify_playlists, spotify_charts, and apple_playlists compare? Which platform seems to favor the most popular tracks?
- In spotify playlist has the modt total streams. I added all the streams in spotify playlist and the result was 4955791 which are more higher than the two remaining.
  
## Advanced Analysis

### Based on the streams data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?
- There are patterns we can see in the graph that i made. As the Key are changing, It is increasing. While in the mode, Major are higher than Minor.

### Do certain genres or artists consistently appear in more playlists or charts? Perform an analysis to compare the most frequently appearing artists in playlists or charts.
- What I did here is I first get the most frequently appearing artists in each playlists and charts. After thst, I sum them all to get who is the top 10 artist that are appearing frequently. The top 1 artist is The weekend followed by taylor swift. while Dr dre and snoopdog are in top 10.

  ## Conclusion
  - This Exploratory Analysis Is hard but when we will analyze each columns and rows, And if we know how to code, We can get this done.
