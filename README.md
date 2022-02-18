# Movies ETL

## Summary
There was a need to create an automated data pipeline that takes in new movie-related data, performs the right transformations, and then loads the data into existing tables. Python code was refactored to create a function that takes in the three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data. An ETL process was then performed by adding the data to a PostgreSQL database.

Four deliverables were completed:

- Wrote an ETL function to read three data files
- Extract and transform the Wikipedia data
- Extract and transform the Kaggle data
- Create the PostgreSQL movie database
