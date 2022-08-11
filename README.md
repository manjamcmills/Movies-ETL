# Movies-ETL
## Overview
The purpose of this challenge was to take all the code we learned in Module 8 and create an "automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables".  This was completed by refactoring code to create one function that read all the data - Wikipedia data, Kaggle metadata, and the MovieLens rating data.  The data was "cleaned" by ETL Process - Extract, Transform,  and Load.  

## Deliverable 1
This was a "test" file to write a function that read in all the 3 data files and created 3 separate DataFrames from the data

## Deliverable 2
In this part, I refactored code to extract and transform the Wikipedia data so that I could then merge it with the Kaggle metadata. I also used a regular expression string and a "try-except" block to catch errors and drop duplicates. 

## Deliverable 3
In this section I used Python, Pandas, the ETL process, and code refactoring to extract and transform the Kaggle metadata and MovieLens rating data. Both the Kaggle and MovieLens data were then transformed to DataFrames.  Next, I merged the Kaggle metadata DataFrame with Wikipedia movies DataFrame to create a new DataFrame called "movies_df".  Lastly, I merged the MovieLens rating data DataFrame with the movies_df DataFrame to create movies_with_ratings_df. 

## Deliverable 4
This last part, I used Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
