# Spotify Song Popularity Analysis 🎵

## 📌 Project Overview
[cite_start]This project analyzes a dataset of **114,000 Spotify tracks** to understand the factors driving song popularity[cite: 11]. Specifically, we investigated two main research questions:
1. [cite_start]**Solo vs. Collaboration:** Do songs performed by multiple artists perform better than solo tracks? [cite: 6]
2. [cite_start]**The "Halo Effect":** Does the presence of a highly popular song in an album boost the popularity of other tracks in that same album? [cite: 5]

## 👥 Contributors (Group B)
* [cite_start]**Priyankkumar Mali** 
* Manas Tripathi
* Nishtha Kapoor
* Kaavya Nagarajan
* Hanzala Syed

## 📊 Key Findings

### 1. Collaboration = Higher Popularity
[cite_start]Our analysis confirmed that collaborative tracks generally outperform solo tracks in popularity[cite: 30].
* [cite_start]**Average Popularity:** Collaborative tracks scored an average of **86.88**, while solo tracks averaged **74.00**.
* [cite_start]**Musical Features:** Collaborative songs tend to have higher **danceability** and wider variations in **energy** compared to solo tracks[cite: 60, 63].

![Popularity Distribution](images/popularity-dist.png)
*Distribution of popularity showing collaborative tracks (blue) vs. solo tracks (orange).*

### 2. Album Dynamics
We found a strong relationship between hit songs and album performance.
* [cite_start]Albums containing at least one "popular" song (score > 50) had significantly higher overall popularity than those without[cite: 90, 92].
* [cite_start]Even when the hit song itself is removed from the calculation, the *remaining* songs in popular albums still score higher (avg ~50) than songs in unpopular albums[cite: 96].

## 🛠️ Methodology
* [cite_start]**Data Cleaning:** Handled duplicates and merged genre columns for tracks with multiple genre tags[cite: 14].
* [cite_start]**Statistical Testing:** Performed T-tests to verify the significance of popularity differences between groups[cite: 24].
* [cite_start]**Visualization:** Used Heatmaps, Histograms, and Boxplots to identify outliers and trends[cite: 21, 25].

## 📈 Visualizations
Below is a heatmap comparing musical attributes (like acousticness, tempo, and energy) between solo and collaborative tracks:

![Feature Heatmap](images/heatmap.png)
[cite_start]**

## 🔗 Live Analysis
[**Click here to view the full interactive Jupyter Notebook Analysis**](https://quantmindx12.github.io/spotify-popularity-analysis/)
