# nosql_challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json

Question 1: Which establishments have a hygiene score equal to 20?
Question 2: Which establishments in London have a RatingValue greater than or equal to 4?
Question 3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"? 
Question 4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas. 

Table of Contents:

Resources: contains json file used in the code.

NoSQLNoSQL_setup_starter.ipynb: contains code used in answering question 1 and 2

NoSQL_analysis_starter.ipynb: contains code used in answering question 3 and 4

References: 

Assisting in coding errors: chat.openai.com

Cheatsheet used to help with NoSQL databases:
https://ugoproto.github.io/ugodoc/sql_nosql_cs/

MongoDB NoSQL:
https://www.mongodb.com/nosql-explained#:~:text=NoSQL%20databases%20(aka%20%22not%20only,wide%2Dcolumn%2C%20and%20graph.

Structure and format for coding:
referenced in class material
