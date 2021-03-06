# Normalize-SQL

## If you recieve the message "Something went wrong, reload?" when viewing the *.ipynb file please go to the following website:
https://nbviewer.jupyter.org/github/rsaigal1/Normalize-SQL/blob/master/Basics.ipynb

Learning How to Normalize Data sets  

In this project, I learned how to:  

Import CSV data into a database. Design a normalized schema for a large, predominantly single table data set. Create tables that match the schema design. Migrate data from unnormalized tables into our normalized tables.  

I will be working with a file of Major League Baseball games from Retrosheet. Retrosheet compiles detailed statistics on baseball games from the 1800s through to today. The main file we will be working from game_log.csv, has been produced by combining 127 separate CSV files from retrosheet, and has been cleaned to remove some inconsistencies. The game log has hundreds of data points on each game which I will normalize into several separate tables using SQL, providing a robust database of game-level statistics.  

In addition to the main file, we have also included three 'helper' files, also sourced from Retrosheet:  

park_codes.csv person_codes.csv team_codes.csv These three helper files in some cases contain extra data, but will also make things easier as they will form the basis for three of our normalized tables.  

An important first step when working with any new data is to perform exploratory data analysis (EDA). EDA gets us familiar with the data and gives us a level of background knowledge that will help us throughout this project. The focus of this project is:  

Becoming familiar, at a high level, with the meaning of each column in each file. Thinking about the relationships between columns within each file. Thinking about the relationships between columns across different files.
