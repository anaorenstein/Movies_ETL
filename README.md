# Movies ETL

### Summary

Amazing Prime Video is a platform for streaming of movies and TV shows on Amazing Prime - the world's largest online retailer. Its team wants to develop an algorithm to predict which low-budget movies will become popular, so they can buy the streaming rights with competitive prices.

The company is sponsoring a *Hack-a-thon*, inviting the team of employees to participate in developing the algorithm to predict the movies collaboratively.

We were approached by the employee in charge to help create the datasets for the *Hack-a-thon*.

We had data from three different sources: Wikipedia data, scraped from the web in JSON format, rating data from MovieLens website, and Kaggle metadata as .csv tables.

We  followed the ETL process: We **extracted** the Wikipedia, Kaggle and ratings data from their respective files, **transformed** the datasets by cleaning them up and joining them together, and **loaded** the cleaned dataset into a SQL database.

To keep the dataset updated on a daily basis, Amazing Prime requested that we create an automated **ETL** **pipeline** that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 

We have created four Jupyter Notebooks with code that compose our ETL pipeline, which are included in this repository. We have also included screenshots of PgAdmin interface that show that the complete tables were added to our PostgreSQL database.

### Software and Data Sources

- ETL pipeline created on Python 3.7.11, Jupyter Notebook 6.4.6, Pandas  1.3.5, PostgreSQL 11, PgAdmin 4.20
- Movie Data sourced from IMDB, Wikipedia, Kaggle, MovieLens 

Due to size of the raw data files, some are not included in this repository.
