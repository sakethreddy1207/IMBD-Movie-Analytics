Project Overview :
I started with a CSV file that contains IMDB movie details such as title, genre, rating, budget, gross revenue, director, and release year.The data had missing values, duplicates, and inconsistent records, so I first performed proper data cleaning (ETL process) in Python.
After cleaning, the processed data was loaded into a MySQL database, where I wrote SQL queries to analyze movie performance.Finally, I created visual dashboards using Matplotlib to understand trends like revenue, ratings, profitability, and director performance.

Tools & Technologies Used :
1.Python (Pandas, NumPy, Matplotlib)
2.MySQL for data storage and SQL analysis
3.SQLAlchemy for database connection
4.Jupyter Notebook for development

Steps Followed : 
Data Cleaning in Python :
1.Removed duplicate movies using title and release year
2.Generated missing movie IDs
3.Fixed invalid ratings, budgets, and gross values
4.Filled missing director and actor names with “Unknown”
5.Handled missing release years using median values

Data Loading to MySQL :
1.Connected Python to MySQL using SQLAlchemy
2.Created a clean movies table
3.Loaded the transformed dataset into the database

SQL Analysis :
1.Found top grossing movies by year
2.Calculated average rating by genre
3.Identified top directors based on ratings
4.Analyzed budget vs gross relationship
5.Determined the most profitable movie genre

Data Visualization :
1.Created bar charts, line charts, and scatter plots using Matplotlib
2.Built simple dashboards to present business insights

Key Insights :
1.Some years consistently produced the highest-grossing movies
2.Movie ratings vary slightly across genres, but certain genres perform better
3.A few directors maintain higher average ratings than others
4.Higher movie budgets generally relate to higher gross revenue
5.One genre clearly stands out as the most profitable overall

