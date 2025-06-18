# IMDb Movie Ratings Analysis

Exploring IMDb movie data using SQL & Python visualizations to uncover trends, rankings, and unique insights. 

---

## Project Overview

This project analyzes a dataset of movies from IMDb using a combination of SQL queries and Python visualizations. It covers areas such as genre distribution, director performance, movie trends over time, and more. Various chart types are used to present data in an engaging and professional way. 

## Dataset Summary

- File Source: 'movie_metadata.csv'
- Source: Kaggle (public dataset)
- Total Columns: 28
- Database Format: SQLite3 (imdb_movies.db)

  ---

## Column Descriptions

This section outlines select columns from the movie_metadata.csv dataset used in this analysis. 

- **color**: Film color format (Black and White)
- **director_name**: Name of the movie's director
- **duration**: Runtime in minutes
- **genres**: Genres assigned to the film (pipe-separated)
- **actor_1_name**: Lead actor's name
- **actor_2_name**: Second-billed actor
- **actor_3_name**: Third-billed actor
- **gross**: Box office earnings (USD)
- **budget**: Estimated producction budget
- **title_year**: Year the movie was released
- **imdb_score**: IMDb rating (1–10 scale)
- **movie_facebook_likes**: Facebook likes for the movie page
- **content_rating**: MPAA rating (e.g., PG-13, R)
- **language**: Language of the film
- **country**: Country of production
  
  ---

## Current Analysis Sections

1. Top 10 Movies by IMDb Score
   - Ranks movies by highest IMDb score.
   - Horizontal bar chart.

2. Most Common Movie Genres
   - Counts most frequent genres.
   - Horizontal bar chart.
  
3. Top Directors by Average IMDb Score
   - Direcctors with highest average rating (min 5 films).
   - Horizontal Bar Chart.

4. Movie Count Over Time
   - Yearly count of films released.
   - Line Chart. 

5. Highest-Grossing Movies
   - Top 10 movies by revenue.
   - Horizontal bar chart.
  
6. Top Actors by Facebook Likes
   - Most liked lead actors.
   - Horizontal bar chart.
  
7. Top 10 Longest Movies
   - Longest runtimes.
   - Horizontal bar chart

8. Average IMDb Score by Genre
   - Avg. score grouped by genre.
   - Horizontal bar chart.
  
9. Average Movie Duration by Genre
   - Avg. runtime by genre.
   - Horizontal bar chart.

10. Average IMDb Score by Year
   - Avg. yearly rating.
   - Scatter plot.

11. IMDb Score vs. Gross Revenue
    - Correlation view.
    - Scatter plot (will update for visual clarity)

12. Fun Queries
    - 12a: Longest movie titles
    - 12b: Shortest movie titles
    - Cleaned to remove whitespace/format issues.

13. Distribution of IMDb Scores
    - Pull all scores for analysis
    - Histogram
   
---

## Upcoming Enhancements

- Add pie or donut charts for **content rating** or **language
  distribution**.
- Use heatmaps for **correlatin matrices**.
- Introduce boxplots to detect **outliers** in **revenue** or **runtime**.
- Add prompt-based AI insights using tags like:
  - Trend Analysis
  - Ranking Analysis
  - Anomaly Detection
 
---
 
## Project Goals

- Clean and explore the dataset
- Analyze distributions of IMDb scores
- Identify top-rated movies
- Examine patterns by genre and duration
- Visualize data with charts

---

## Tools Used

- SQL (SQLite3)
- Python 3.11
- JupyterLab / Jupyter Notebook
- Pandas
- Matplotlib

---

## Project Insights

1. **Drama is the Most Dominant Genre**
   Drama appears more frequently than any other genre, either alone or in
   combination with others, confirming its strong presence across all decades
   of filmmaking.

2. **Christopher Nolan Leads in Average Ratings**
   Among directors with at least five movies, Christopher Nolan consistently
   receives the highest IMDb scores - showcasing both quality and
   consistency.

3. **Movie Production Peaked Around 2010-2015**
   The number of movies released each year surged dramatically during the
   2000's, peaking around 2014 before dipping- likely due to shifts in
   digital media consumption.

4. **High IMDb Scores Don't Always Equal High Revenue**
   A scatter plot comparing IMDb scores and box office gross reveals weak
   correlation, suggesting factors like marketing and franchise popularity
   influence revenue more than critical acclaim. 

---

## Project Structure
IMDb Movie Project

- imdb.movies.db
- movie_analysis.ipynb
- README.md
- images/ (optional: for saved plots or screenshots)

---

## How to Run

1. Clone or download the repo
2. Open 'Movie_Analysis.ipynb' in Jupyter
3. Run the notebook to reproduce the analysis

---

## Conclusion 

This project demonstrates the use of structured queries and data visualization to tell a story with movie data. It's still evolving - more creative visuals, project insights, and category-based recommendations are coming next. 

---

## Author

Hallene Brooks 
GitHub | (https://github.com/HCBrooks-lab) 
