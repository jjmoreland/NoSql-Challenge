# NoSql-Challenge

For this challenge, we will use a Mongo database to evaluate food establishments in the UK for food magazine "Eat, Safe, Love". The analysis will help journalists and food critics decide where to focus future articles.  The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating.  

## Part 1 and Part 2
For both Part 1 and Part 2, database set up and datebase update(s) are found on NoSql_setup_starter.ipynb
  - Update(s) include:
    - Add restaurant "Penang Flavours" to the database.
    - Find BusinessTypeID for "Restaurant/Cafe/Canteen" and update Penang Flavours to corresponding BusinessTypeID
    - Check how many documents contain the Dover Local Authority and then remove establishments within the Dover Local Authority from the database
    - Update latitude and longitude values to decimals

## Part 3
For Part 3, specific analysis questions are found on NoSql_analysis_starter.ipynb
  - Determine which establishments have a hygiene score equal to 20.
  - Determine which establishments in London have a RatingValue greater than or equal to 4.
  - Find the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to "Penang Flavours."
  - Determine how many establishments in each Local Authority area have a hygiene score of 0
