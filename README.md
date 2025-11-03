# IMDb Movie Ratings Analysis

Analyzing IMDb movie datas with SQL & Python visualizations to uncover trends, rankings, and unique insights. 

---

## Overview

This project explores a dataset of IMDb movies, examining genre trends, director performance, and yearly performance patterns. It combines SQL queries with Python charts for a clear, engaging presentation. 

---

## Dataset Summary

- File: 'movie_metadata.csv'
- Source: Kaggle (public dataset)
- Total Columns: 28
- Database Format: SQLite3 (imdb_movies.db)

---

## Visual Insights

### IMDb Rating Distribution by Decade
This boxplot illustrates how IMDb rating distributions have evolved across decades. Each box represents the interquartile range (middle 50% of ratings), while later decades show broader variations and slightly lower averages. 

**Figure:** `imdb_rating_by_decade.png`

---

## Key Analysis Sections 

## 1. Top 10 Movies by IMDb Score 
## 2. Most Common Genres 
## 3. Top Directors by Average Score
## 4. Movie Count Over Time
## 5. Highest-Grossing Movies 
## 6. Average IMDb Score by Year
## 7. IMDb Score vs. Gross Revenue
## 8. Fun Queries - Longest & Shortest Titles
## 9. Distribution of IMDb Scores

---
 
## Project Insights

1. **Drama is the Most Dominant Genre:**
   Drama appears more frequently than any other genre, either alone or in
   combination with others, confirming its strong presence across all decades
   of filmmaking.

2. **Christopher Nolan Leads in Average Ratings:**
   Among directors with at least five movies, Christopher Nolan consistently
   receives the highest IMDb scores - showcasing both quality and
   consistency.

3. **Movie Production Peaked Around 2010-2015:**
   The number of movies released each year surged dramatically during the
   2000's, peaking around 2014 before dipping- likely due to shifts in
   digital media consumption.

4. **High IMDb Scores Don't Always Equal High Revenue:**
   A scatter plot comparing IMDb scores and box office gross reveals weak
   correlation, suggesting factors like marketing and franchise popularity
   influence revenue more than critical acclaim.

5. **Later Decades Show Greater Rating Variability:**
   As film production expanded from the 1980s onward, IMDb ratings became more
   dispersed, with both higher highs and lower lows. This pattern shows that as
   industry scaled up and diversified globally, the range of film quality and
   audience reception widened. 

---

## Tools Used

- SQL (SQLite3)
- Python 3.11
- Pandas, Matplotlib, Seaborn
- Jupyter Notebook

---

## Recent Additions

- Added "Movies Released per Decade" visual to contextualize rating trends.
- Cleaned and restructured plotting cells.
- Improved figure export consistency across visuals.

---

## Upcoming Enhancements

- Advanced visualizations
- Time-Series Trends
- Predictive Insights
- Interactie Elements
- Additional Queries
- Improved Scatterplot Clarity
- More Detailed Data Cleaning Notes

## How to Run

1. Clone or download the repo
2. Open 'Movie_Analysis.ipynb' in Jupyter
3. Run the notebook to reproduce the analysis

---

## Conclusion 

This analysis provides a comprehensive exploration of IMDb data using SQL and Python. It reveals across genres, directors, and decades, highlighting how data-driven storytelling can uncover both creative and commercial trends. 

---

## Author

Hallene Brooks 
GitHub | (https://github.com/HCBrooks-lab) 
