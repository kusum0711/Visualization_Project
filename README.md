# Spotify Top 2000 Tracks Visualization Project

## Overview

This project is a data visualization analysis of the top 2000 tracks on Spotify. It includes audio statistics and insights drawn from a dataset comprising tracks released between 1956 and 2019 by various renowned artists including Queen, The Beatles, and Guns N' Roses.

The project focuses on visualizing patterns and relationships among audio features like energy, danceability, loudness, speechiness, valence (positivity), and popularity using various plots such as box plots, scatter plots, and bar charts.

---

## Dataset Description

The dataset was sourced via [Sort Your Music by @plamere](http://sortyourmusic.playlistmachinery.com/) using the Spotify API. It includes the following columns:

- `ID`: Track ID
- `Title`: Track name
- `Artist`: Artist name
- `Top Genre`: Genre of the track
- `Year`: Year of release
- `Beats per Minute (BPM)`: Song tempo
- `Energy`: Measures intensity and activity
- `Danceability`: Suitability for dancing
- `Loudness`: Overall loudness of the track
- `Valence`: Musical positiveness
- `Length`: Duration in seconds
- `Acoustic`: Acoustic nature of the track
- `Speechiness`: Presence of spoken words
- `Popularity`: Popularity score (0-100)

---

## Analytical Questions & Key Insights

1. **How does the energy level of songs vary across different genres?**
   - Genres like *Dance Pop* and *Big Room* show high energy.
   - *Neo Mellow* and *Acoustic Pop* have lower average energy.
   - Popular songs in some genres (e.g., Dance Pop) maintain popularity regardless of energy level.

2. **Is there a relationship between speechiness and song popularity?**
   - A slight upward trend was observed, particularly from 2014–2019.
   - Songs like *"Youngblood"* and *"bad guy"* exemplify higher speechiness and popularity.

3. **Which artists are most likely to produce tracks in the Top 2000?**
   - Artists like *Coldplay* rank high in terms of average popularity among their top tracks.

4. **Does loudness influence valence (positivity)?**
   - A weak positive correlation exists; louder tracks tend to have slightly higher valence.
   - Most tracks cluster between -10 to -6 dB in loudness and 40–60 in valence.

5. **How has song length changed over the decades?**
   - 1950s–60s: ~180 seconds
   - 1970s–90s: Increased to ~250–300 seconds
   - Post-2000s: Stabilized around 200–250 seconds
   - Shorter songs from earlier decades, such as *"At Last"* and *"Can’t Help Falling in Love"*, still maintain high popularity.

---

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Spotify API
- Data sourced from [Kaggle](https://www.kaggle.com/plamere) and [Sort Your Music](http://sortyourmusic.playlistmachinery.com/)

---


