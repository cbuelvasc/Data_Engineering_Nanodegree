# Sparkify Postgres ETL

This is the first project to send for the Data Engineering Nanodegree like a requirement of the program.

# Goals

The project pretends to look at some specific goals in the line of knowledge for nanodegree as Data Modeling, Star Schema and ETL in Postgres using Python


## Context

The point is centrally the data analytics we can extracting that tracking of the music that people listening, Sparkify is a startup and wants to know the clients want, for these goals the data is contained in JSON metadata.

We are asked to start this project to analyze all the data and to be able to learn more about users' musical tastes in the future.

## Database Schema
## Database Schema
The database schema used for this exercise is the Star Schema and its conformed of the next way:
#### Fact Table: 
**songplays** 
#### Dimension Tables:
**users**
**songs**
**artists** 
**time** 


### Step by Step followed

1) Run in console:
 ```
python create_tables.py
```

2) Used Jupyter Notebook to interactively verify that all tables were created correctly:
```
test.ipynb
```

3) To process the data and fill the tables of all the follow-up to the users, execute the following file on the Jupiter notebook;
```
etl.ipynb
```

4) Run in console:
 ```
python etl.py
```
2) Finally, to verify that everything is correctly processed and the tables properly filled you must use Jupyter Notebook:
```
test.ipynb
```

### Example Query and Results

[Example Query and Results](query-data.jpg "Example")


## Author

* **Carmelo Buelvas** - [Github](https://github.com/cbuelvasc) - [LinkedIn](https://www.linkedin.com/in/cbuelvasc/)
