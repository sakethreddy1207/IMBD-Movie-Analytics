## IMDB Movie Dataset Analysis - P1
---
## Project Overview 

This project focuses on analyzing an IMDB movie dataset using Python and MySQL.
The dataset was provided in CSV format and includes details such as movie title, genre, rating, budget, gross revenue, director, and release year.
Since the raw data contained missing values, duplicate records, and inconsistent entries, I first performed data cleaning and transformation using Python as part of the ETL process.
After preparing the clean dataset, I loaded it into a MySQL database and used SQL queries to analyze movie performance. Finally, I created visual dashboards using Matplotlib to explore trends related to revenue, ratings, profitability, and director performance.

---
## Repository Contents
 - `IMDB Movie Business Rules and dashboard_problems statements.txt`
 
    This file includes the business rules followed during the ETL process and the problem statements used for building the dashboards.

- `imdb_ddl.sql`

   SQL script used to create the database and table structure for storing the cleaned IMDB data in MySQL.

- `imdb_movies.csv`

    Raw IMDB movie dataset in CSV format used as the primary data source for this project.

- `IMDB Movie Analytics.ipynb`

    Main Jupyter Notebook containing the complete ETL process, SQL analysis, and data visualizations.
---
## Tools & Technologies Used 
- Python (Pandas, NumPy, Matplotlib)
- MySQL for data storage and SQL analysis
- SQLAlchemy for database connection
- Jupyter Notebook for development
---
## Steps Followed 
## Data Cleaning in Python 
- Removed duplicate movies using title and release year
- Generated missing movie IDs
- Fixed invalid ratings, budgets, and gross values
- Filled missing director and actor names with “Unknown”
- Handled missing release years using median values
## Data Loading to MySQL 
- Connected Python to MySQL using SQLAlchema
- Created a clean movies table
- Loaded the transformed dataset into the database
## SQL Analysis 
- Found top grossing movies by year
- Calculated average rating by genre
- Identified top directors based on ratings
- Analyzed budget vs gross relationship
- Determined the most profitable movie genre
## Data Visualization 
- Created bar charts, line charts, and scatter plots using Matplotlib
- Built simple dashboards to present business insights
---
## Key Insights 
- Some years consistently produced the highest-grossing movies
- Movie ratings vary slightly across genres, but certain genres perform better
- A few directors maintain higher average ratings than others
- Higher movie budgets generally relate to higher gross revenue
- One genre clearly stands out as the most profitable overall

