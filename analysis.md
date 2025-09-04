# Kannada Music Spotify Dataset Analysis

This analysis explores a curated dataset of Kannada songs sourced from Spotify, focusing on key musical and popularity metrics. The workflow and findings are summarized below:

## Data Collection & Preparation
- **Source:** Songs were fetched using the Spotify API, including metadata such as name, album, artist, release date, length (ms), popularity, and Spotify URL.
- **Cleaning:** Missing values were removed, song lengths converted to minutes, and release years extracted. Artist names were standardized.

## Exploratory Analysis
- **Dataset Size:** The cleaned dataset contains dozens of songs spanning from 2017 to 2025.
- **Artists & Albums:** The dataset features a diverse range of artists and albums, with some artists and albums contributing multiple tracks.
- **Song Length:** Most songs range between 2.5 to 5 minutes, with a few outliers.
- **Popularity:** Popularity scores (0-100) vary widely, with some tracks reaching above 80.

## Key Insights
- **Top Artists:** Artists like Arjun Janya, B. Ajaneesh Loknath, and Sanjith Hegde appear frequently.
- **Popular Songs:** The most popular tracks score above 80, while the average popularity is around 50-60.
- **Release Trends:** There is a steady output of Kannada songs each year, with peaks in recent years.
- **Collaborations:** Most tracks are solo performances, but collaborations are present.
- **Albums:** Certain albums, such as "Kotigobba 3" and "Param Sundari," have multiple entries.

## Visualizations
- **Distributions:** Histograms illustrate the spread of song lengths and popularity.
- **Bar Charts:** Top artists and albums are highlighted by song count and average popularity.
- **Trends:** Line plots show song releases and average song length by year.
- **Word Cloud:** Common words in song titles are visualized.
- **Correlation:** A heatmap reveals relationships between popularity, length, and release year.

## Summary Statistics
- **Most Common Artist:** Arjun Janya (multiple songs).
- **Most Popular Song:** "Pardesiya - From Param Sundari" (popularity 82).
- **Longest Song:** "Oh Anahita (From Ibbani Tabbida Ileyali)" (~5.5 minutes).
- **Shortest Song:** "Kadalanu (From Sapta Sagaradaache Ello - Side A)" (~1.7 minutes).

---

This analysis provides a comprehensive overview of Kannada music trends on Spotify, highlighting popular artists, albums, and evolving song characteristics.