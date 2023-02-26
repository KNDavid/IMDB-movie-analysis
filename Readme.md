# Investigate a Dataset: IMDB Movie
This xplores the IMDB movies dataset which contains movies from 1960 to 2015. The dataset has 10866 rows and 21 columns, including `id`,`imdb_id`, `popularity`, `budget`, `revenue`, `original_title`, `cast`, `homepage`, `director`, `tagline`, `keywords`, `overview`, `runtime`, `genres`, `production_companies`, `release_date`,`vote_count`,`vote_average`,`release_year`, `budget_adj`, and `revenue_adj`.

The objective of this project is to answer multiple questions, including:

- What kind of properties are associated with movies that have high revenues?
- What kind of properties are associated with movies that have high ratings?
- Does the popularity of the movie depend on the budget used?
- Analysis of the production companies
- Analysing and answering the questions about the movie genres
- Questions regarding the movie directors
- The movie with the highest revenue and its relation with the highest profit
- The movie with the highest rating

## Data Cleaning
In the data cleaning process, we performed the following tasks:

- Removed the duplicate values
- Removed the columns that were not needed for our analysis
- Changed the data type of the release_date column
- Replaced the zero values with their mean values
- Created a profit column to analyse which movie made profits

## Data Exploration
We used scatter matrices to evaluate the relationship between a combination of variables. We also explored the following:

- Does the popularity of the movie depend on the budget used?
- What properties are associated with movies with high revenue?
- What properties are associated with movies with high ratings?
- Questions regarding the years

### Top 10 Values
In our exploratory analysis, we created a function that allowed us to plot a bar chart for the top 10 values in different columns. We used this function to answer the following questions:

- What are the top 10 most profitable movies?
- What are the top 10 most rated movies?
- What are the top 10 production companies?
- What are the top 10 genres?
- What are the top 10 directors?

## Conclusion
This project explored the IMDB movies dataset to answer multiple questions about movies. The analysis provided insights into the properties of movies with high revenues, high ratings, and high profits. We also analysed production companies, genres, and directors. The top 10 values were also explored in different columns.