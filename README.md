# Modeling Sparkify Database with Postgres

## Project Summary
This project models & transforms the song & user data for the Sparkify company using Postgres so that it can be analyzed by their analytical team. It uses a star-schema with Dimension & Fact tables to make it easy to write analytical SQL queries on the database. It uses a Python script to ETL the data from the song & log files to the Postgres database.

## How to run the project
Please run the following Python scripts :
1. create_tables.py --> It creates the database & the Dimension & Fact tables for the Sparkify database
1. etl.py --> It loads the data into the Sparkify database from the song & log files

## Explanation of files
You'll find the following files in the repo :
1. test.ipynb displays the first few rows of each table to let you check your database.
1. create_tables.py drops and creates your tables. You run this file to reset your tables before each time you run your ETL scripts.
1. etl.ipynb reads and processes a single file from song_data and log_data and loads the data into your tables. This notebook contains detailed instructions on the ETL process for each of the tables.
1. etl.py reads and processes files from song_data and log_data and loads them into your tables. You can fill this out based on your work in the ETL notebook.
1. sql_queries.py contains all your sql queries, and is imported into the last three files above.
1. README.md provides discussion on your project.
