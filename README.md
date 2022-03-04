# Movies-ETL

## Purpose

Amazing Prime needs an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables for a hackathon. This repository takes in three files (Wikipedia data, Kaggle metadata, and MovieLens rating data) and performs the ETL process by adding the data to a PostgreSQL database.

## Resources

Datasets being used are: movies_metadata.csv (included in the Resources folder), ratings.csv, and wikipedia-movies.json (included in the Resources folder).

Also included in the resources folder are screenshots of two queries performed on the movies and ratings tables (both created with ETL_create_database), which show the number of rows in each table.

## Summary

The data had to be extracted and cleaned, which was a lengthy process because there were inconsistencies across the various datasets, empty cells, and other error-producing dilemmas. Although a more thorough cleaning process would have been possible, the data has been sufficiently produced in an adequate manner that suits the needs for the hackathon. 
