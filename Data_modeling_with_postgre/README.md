<h2>Summary of the Project</h2>

This project make the raw data usable to do data-analytic method and make the automation of ETL Process of 
Song_Data. 

<h2>Schema</h2>

songplays is composed of
songplay_id int, start_time time, user_id int, level varchar, song_id varchar, artist_id varchar, session_id int, location varchar, user_agent varchar


users is composed of
user_id int, first_name varchar, last_name varchar, gender varchar, level varchar


songs is composed of
song_id varchar,title varchar,artist_id varchar, year int, duration numeric


artists is composed of
artist_id varchar, name varchar, location varchar, latitude numeric, longitude numeric


time is composed of
start_time time,hour int ,day int ,week int ,month int ,year int ,weekday int


<h2>How to run the code</h2>

To run the code, follwing the below stpes

1. open terminal and python create_tables.py
2. open etl.ipynb and execute all cells inside the file
3. To confirm the code and database, you are going to test.ipynb and test the code before executing etl.ipynb.

<h2></h2>

