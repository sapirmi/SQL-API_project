# SQL_project

## About the DataSet
The dataset was taken from kaggle (link to the dataset - https://www.kaggle.com/andrewmvd/udemy-courses).
Every row represent sa single course and its' details - ID, name, URL address, paid or free, price, number of subscribers,
number of reviews, number of lectures, level, content dutation, published timestamp, and subject.

## About the project
My goal in this project was to practice SQL queries.\
After writing 6 queries, I have decided to use another table to make the queries harder and uniqe.\
For the second table ("rating"), I used REST API to pull more data about the courses from the first table  from udemy, specifically rating score.\
Later, I wrote queries for the rating table and queries that combine both of the tables.

##  Tools
1. Python - Pandas, Json.
2. SQL - Sqlite3 Python's library.
3. REST API - API requests Python's library.

## Questions
Q1 - What are the top 5 courses in each subject?\
Q2 - What are the 10 most popular courses?\
Q3 - Which year had the most courses published?\
Q4 - Which course has the highest price per lecture?\
Q5 - What is the average price per lecture out of all paid courses?\
Q6 - Which course has the max price for each month?\
Q7 - What are the top 10 courses with the highest rating avarage score?\
Q8 - Build a table including courses' id, title, and avarage rating score.
