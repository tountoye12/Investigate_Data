# (Dataset Exploration Title)
## by (Mamadou Adama Diallo)

In this project, I'll analyze a dataset and then communicate our findings about it. I will use the Python libraries NumPy, pandas, and Matplotlib during this work.

## Dataset
The dataset contains information about 10,000 movies collected from The Movie Database(TMDb).

- Certain columns ‘genres’, contain multiple values separated by pipe (|) characters.
- There are some odd characters in the ‘cast’ column. They are not important because this columns will not be included in our analysis.
- The final two columns budget_adj, revenue_adj show the budget and revenue of the associated movie in terms of 2010 dollars accounting for inflation over time.


## Summary of Findings

* We notice a strong correlation between the revenue and budget, vote count, popularity.

* The adventure movie has a good revenue

* The films that have a very good revenue are films that have a vote around 7 and have a big budget


## Key Insights for Presentation
During the data exploration, I find, there was much missing values,
I split the data by pipe (|) characters in the genres column and put the result in new column named genre_movie
