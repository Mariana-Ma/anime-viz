# Anime Ratings vs Popularity Visualization

## Overview
This project visualizes how anime ratings are influenced by popularity and genre using an interactive scatter plot. Users can click on points to view an anime’s poster and description.

Built with **JavaScript**, **D3**, and **Observable Plot**. This project focuses on creating an **interactive, web-based data visualization** of data from [MyAnimeList](https://myanimelist.net/).

---

## Demo
[View Live Site]([https://your-username.github.io/anime-project/](https://mariana-ma.github.io/anime-viz/))

---

## Features
- Interactive scatter plot of anime popularity vs. average rating  
- Color-coded by genre  
- Click a dot to reveal anime title, genre, synopsis, and poster  
- Displays top 300 most popular anime to reduce clutter  

---

## Dataset
The visualization uses two CSV files:

1. **anime.csv** – Main dataset with:
   - `anime_id`, `title`, `score`, `popularity`, `members`, `synopsis`, `image_url`, etc.
2. **anime_primary_genre.csv** – Mapping of anime to their primary genre  

Both datasets are included in the repo for reproducibility.

---
