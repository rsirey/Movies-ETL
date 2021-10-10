# Movies - ETL Analysis

## Project Overview

Extracting data from three main sources, transforming it to serve Amazing Prime’s  Hackathon, and loading it into a PostgreSQL database.

## Resources

### Data Sources 

* wikipedia-movies.json
* movies_metadata.csv
* ratings_csv

### Software 

* Python
* Anaconda
* Jupyter Notebook
* PostgreSQL
* pgAdmin


## Results

An ETL function reads three separate data files creates data frames based on the information.

TV shows, duplicates, adult movies, and redundant data were removed from the Wikipedia and Kaggle data and then the data merged based largely on the Kaggle inputs with Wikipedia data filling in where need be.


## Movies-ETL Summary

The PostgreSQL database provides Amazing Prime’s Hackathon participants with a usable set of data for analysis.
