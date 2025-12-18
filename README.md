# Spotify Song Popularity Analysis 🎵

## 📌 Project Overview
[This project analyzes a dataset of **114,000 Spotify tracks** to understand the factors driving song popularity[cite: 11]. Specifically, we investigated two main research questions:
1. [**Solo vs. Collaboration:** Do songs performed by multiple artists perform better than solo tracks? [cite: 6]
2. [**The "Halo Effect":** Does the presence of a highly popular song in an album boost the popularity of other tracks in that same album? [cite: 5]

## 📊 Key Findings

### 1. Collaboration = Higher Popularity
[Our analysis confirmed that collaborative tracks generally outperform solo tracks in popularity[cite: 30].
* [**Average Popularity:** Collaborative tracks scored an average of **86.88**, while solo tracks averaged **74.00**.
* [**Musical Features:** Collaborative songs tend to have higher **danceability** and wider variations in **energy** compared to solo tracks[cite: 60, 63].

![Popularity Distribution](images/popularity-dist.png)
*Distribution of popularity showing collaborative tracks (blue) vs. solo tracks (orange).*

### 2. Album Dynamics
We found a strong relationship between hit songs and album performance.
* [Albums containing at least one "popular" song (score > 50) had significantly higher overall popularity than those without[cite: 90, 92].
* [Even when the hit song itself is removed from the calculation, the *remaining* songs in popular albums still score higher (avg ~50) than songs in unpopular albums[cite: 96].

## 🛠️ Methodology
* [**Data Cleaning:** Handled duplicates and merged genre columns for tracks with multiple genre tags[cite: 14].
* [**Statistical Testing:** Performed T-tests to verify the significance of popularity differences between groups[cite: 24].
* [**Visualization:** Used Heatmaps, Histograms, and Boxplots to identify outliers and trends[cite: 21, 25].


## 🔗 Live Analysis
[**Click here to view the full interactive Jupyter Notebook Analysis**](https://quantmindx12.github.io/spotify-popularity-analysis/)
