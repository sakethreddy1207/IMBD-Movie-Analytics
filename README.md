## IMDB Movie Dataset Analysis - P1
---
## Project Overview :

I started with a CSV file that contains IMDB movie details such as title, genre, rating, budget, gross revenue, director, and release year.The data had missing values, duplicates, and inconsistent records, so I first performed proper data cleaning (ETL process) in Python.

After cleaning, the processed data was loaded into a MySQL database, where I wrote SQL queries to analyze movie performance.Finally, I created visual dashboards using Matplotlib to understand trends like revenue, ratings, profitability, and director performance.

---
## Tools & Technologies Used :
- Python (Pandas, NumPy, Matplotlib)
- MySQL for data storage and SQL analysis
- SQLAlchemy for database connection
- Jupyter Notebook for development
---
## Steps Followed : 
Data Cleaning in Python :
- Removed duplicate movies using title and release year
- Generated missing movie IDs
- Fixed invalid ratings, budgets, and gross values
- Filled missing director and actor names with “Unknown”
- Handled missing release years using median values
---
## Data Loading to MySQL :
- Connected Python to MySQL using SQLAlchema
- Created a clean movies table
- Loaded the transformed dataset into the database
---
## SQL Analysis :
- Found top grossing movies by year
- Calculated average rating by genre
- Identified top directors based on ratings
- Analyzed budget vs gross relationship
- Determined the most profitable movie genre
---
## Data Visualization :
- Created bar charts, line charts, and scatter plots using Matplotlib
- Built simple dashboards to present business insights
---
## Key Insights :
- Some years consistently produced the highest-grossing movies
- Movie ratings vary slightly across genres, but certain genres perform better
- A few directors maintain higher average ratings than others
- Higher movie budgets generally relate to higher gross revenue
- One genre clearly stands out as the most profitable overall

