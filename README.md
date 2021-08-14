# Movies-ETL


## Overview
The purpose of this project was to create an automated pipeline to take in new data, perform the appropriate transformations, and load the clean data into existing tables. The goal was to create one function that takes in the three files (Wikipedia data, Kaggle metadata, and the MovieLens rating data) and carries out the ETL process resulting in two clean data tables in a PostgreSQL database.

## Resources
- Data Sources
    - Wikipedia Movie Data: [Wikipedia API](https://www.mediawiki.org/wiki/)
        - wikipedia-movies.json
    - Kaggle Data (movies _metadata.csv & ratings.csv) 
        - [The Movies Data Set](https://www.kaggle.com/rounakbanik/the-movies-dataset)
        - [Movie Lens Data Set](https://grouplens.org/datasets/movielens/)

- Software: 
    - Python 3.7.10 
    - Jupyter Notebook, 6.3.0
    - pgAdmin4 version 5.5