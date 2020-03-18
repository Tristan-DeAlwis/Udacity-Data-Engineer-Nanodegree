# Data Modeling with Postgres | Schema for Song Play Analysis
## Tristan De Alwis
### 17 - March - 2020

In this project a schema for song play analysis is made.

Data is then extracted from the source, transformed using Pandas DataFrame, and loaded into the database. Two sets of data is used in the ETL process; song and log data. Song data provides song and artist information, while Log data is more extensive; providing covers song, artist and some metadata about each song. Log data is more extensive, providing artist and artist metadata.

### Prerequisites for running the program

Prerequisites for running the project is python 3.x and postgres with a default database named "studentdb" available.

### Starting the program

Execute "create_tables.py". This will create a fresh instance of the sparkifydb with empty tables.
Execute "etl.py". This will load the data into the tables