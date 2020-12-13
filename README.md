# Data Modeling with Apache Cassandra
This is a data modeling with Apache Cassandra project for the Udacity Data Engineering Nanodegree program.

## Project Overview
In this project we'll extract event data from various CSV files which will be loaded into a single CSV file. We'll model the Apache Cassandra database using the following three queries:

   1. Find songs by session item.
 
   2. Find songs by session.
   
   3. Find users by song.

Upon these queries we'll design and create the tables and then load data into the target tables from our CSV data source. Finally, we'll execute the queries to check if the data has been inserted as expected.

## Installation
### Clone
```sh
$ git clone https://github.com/amosvoron/udacity-cassandra.git
```

## Repository Description

```sh
- event_data/                          # directory with CSV data files                    
- create_tables.py                     # python script for database and table creation 
- Project_1B_Project_Template.ipynb    # project template notebook 
- project.ipynb                        # project notebook
- README.md                            # README file
- LICENCE.md                           # LICENCE file
```

## License

MIT