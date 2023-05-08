# Exploratory Data Analysis on Spotify Dataset 1920-2020

This project is an exploratory data analysis (EDA) on the Spotify dataset from 1920-2020. The goal of this project is to gain insights into the music trends and patterns over the past century using Python visualization tools such as Matplotlib, Seaborn, and Plotly.

## Dataset

The Spotify dataset used for this analysis was obtained from Kaggle (https://jovian.ai/zhangxm963/spotify-dataframe/v/39/files?filename=spotify-dataset-19212020-160k-tracks/data.csv). It contains over 160,000 tracks with various features such as danceability, energy, loudness, and tempo.

## Tools

The analysis was performed using Python 3.8. The following Python libraries were used:

• Pandas: for data manipulation and analysis <br>
• Matplotlib: for basic data visualization
• Seaborn: for more advanced data visualization
• Plotly: for interactive data visualization

## Analysis

The analysis was divided into several parts, including:

• Data cleaning and preprocessing: removing duplicate tracks, handling missing values, and converting data types as necessary
• Overview of the dataset: exploring the distribution of features such as danceability, energy, loudness, and tempo
• Trends over time: analyzing the changes in music trends over the past century, such as the popularity of certain genres and the evolution of musical features
• Correlations between features: examining the relationships between various features and identifying any patterns or trends

## Summary of Analysis

1.   The dataset is from Spotify and contains 174389 songs from the year 1920 to the year 2021.

2.  The dataset contains 174389 rows and 19 columns.

3.  There are no missing values in the dataset.

4.  There are 2159 duplicate rows in the dataset. So the final dataset contains 172230 rows after dropping the duplicate rows.

5.  The number of songs every year has been increasing overall. But there is a sudden decrease in the number of songs after 2020. This is because the dataset contains the songs only up to January 2021.

6.  The most popular songs have a fairly recent release date, i.e, in 2021 or 2020. 

7.  The song “White Christmas” has the highest popularity.

8.  Most songs are between 3 to 4 minutes long.

9.  Around ~6.8% of the songs in the dataset have parental advisory labels associated with them.

10.  Energy songs are a new trend in recent years.
 
11.  Acoustics have shown a steep decline after the 1960s. It means music makers nowadays are more inclined towards the electronic side of music rather than acoustic means.

12.  The overall acoustics has decreased and the energy has increased over time.

13.  The song “Funky Cold Medina” is the most danceable song.

14.  The danceability of the songs has increased over the years.

15.  Tadeusz Dolega Mostowicz is the artist with most songs.
 
16.  It seems like there are some differences between the two songs' subgroups in almost all of the audio features. That is, the most popular songs are more “energetic”, “danceable” and have a higher “explicitness” value. The rest of the songs score higher in the “acousticness” and “valence” categories, which can be interpreted as conveying more positivity, by Spotify’s definitions of the features.

17.  It is clearly visible that dancebility decreased significantly during World War 2.
 
18.  There are a couple of differences in the music of the two eras: firstly, post-1990s music is more “energetic”, “danceable” and “explicit”. Whereas other features like “valence” and “liveliness” are pretty similar amongst the two. Pre-1990s music also tends to score higher on “acousticness” and “instrumentalness”.

19.  'Popularity' and 'Danceability' are positively correlated, which implies that, as the popularity of the song increases, the danceability score for that song also increases.

20.  'Popularity' and ‘Instrumentalness’ are negatively correlated, which means that an increase in one leads to a decrease in the other and vice versa.

21.  It is interesting that acousticness and energy and loudness have a negative high correlation, which is logical because acoustic music is often quiet and calming.

22.  There is a strong positive correlation between energy and loudness.
 
23.  Also, there is a positive correlation between valence and danceability.

24.  There seems to be a strong negative correlation between acousticness and energy.

25.  We observe that the average duration of the song has first increased since the 1920s, but has remained more or less the same ever since and is slowly decreasing during the past years.

26.  In March of 2020, the world went under a complete lockdown. It's natural to wonder what were some of the top songs released back then. The title of the songs seems to be mirroring the world's mood back then: "No idea", "Don't Start Now", "Maniac", "Break My Heart", "you broke me first" and more.

27.  625 artists have 'Young' in their names and they usually make more danceable, energetic, loud, and explicit music.



