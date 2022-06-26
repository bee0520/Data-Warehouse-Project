# Data-Warehouse-Project

### Introduction

In this project, we would help one music streaming startup to move their user base and song database processes on to the cloud. Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app. I would build an ETL pipeline that extracts their data from S3, stages them in Redshift, and transforms data into a set of dimensional tables for their analytics team.

###  Database Schema for Song Play Analysis

**Fact Table**
songplays - records in event data associated with song plays

**Dimension Tables**
users - users in the app
songs - songs in music database
artists - artists in music database
time - timestamps of record

### Project Files

1. `create_table.py` is where you'll create your fact and dimension tables for the star schema in Redshift.
2. `etl.py` is where you'll load data from S3 into staging tables on Redshift and then process that data into your analytics tables on Redshift.
3. `sql_queries.py` is where you'll define you SQL statements, which will be imported into the two other files above.
4. `README.md` is where you'll provide discussion on your process and decisions for this ETL pipeline.


### How to Run

1. Create tables by running `create_tables.py`.

2. Execute ETL process by running `etl.py`.







