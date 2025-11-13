# Phase 2: Movie Studio Data Analysis

## Project Overview
This project analyzes movie data to provide actionable insights for a new movie studio. 
Using datasets from Box Office Mojo and IMDB (SQLite database `im.db`), the analysis explores which types of movies perform best and why.  
The goal is to help the studio make data-driven decisions about which movies to produce.

---

## Business Questions
1. **Which studios consistently produce the highest-rated movies?**  
2. **Which genres receive the highest audience ratings?**  
3. **Which directors consistently produce high-rated movies?**  
4. **Does movie runtime affect audience ratings?**

---

## Data Sources
- `bom.movie_gross.csv.gz` : Box Office Mojo movie financial data  
- `im.db` : IMDB SQLite database containing movie basics, ratings, directors, writers, and cast  
- Cleaned and merged datasets combining movie info, ratings, genres, and studios  

---

## How to Run
1. Clone this repository.  
2. Ensure the `data/` folder contains all CSV files and `im.db`.  
3. Open `student.ipynb` in Jupyter Notebook.  
4. Run all cells to reproduce analysis, visualizations, and insights.  

---

## Repository Structure
- `student.ipynb` : Main analysis notebook with all data cleaning, merging, analysis, and visualizations  
- `presentation.pdf` : PDF of the presentation slides  
- `data/` : Folder containing all raw datasets and `im.db`  

---

## Key Insights
1. **Genres:** Drama and Biography movies consistently receive higher audience ratings.  
2. **Studios:** Certain studios produce high-rated movies more consistently than others.  
3. **Directors:** Some directors are more likely to create high-rated movies.  
4. **Runtime:** Movie runtime has minimal impact on audience ratings.  

---

## Recommendations
1. Focus on producing **Drama and Biography films** to maximize audience ratings.  
2. Partner with **high-performing studios and directors** to improve quality and ratings.  
3. Use audience ratings data to **guide casting and creative decisions**, rather than focusing solely on runtime.  
