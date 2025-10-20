# NETFLIX-MOVIES-AND-TV-SHOWS-
Task 1 of internship by elevate labs  i.e. DATA CLEANING AND PROCESSING

Summary of Cleaning Operations-

Step                  |  Description                                                |  Result              
----------------------+-------------------------------------------------------------+----------------------
Duplicate Removal     |  Removed identical rows                                     |  0 duplicates removed
Missing Titles        |  Dropped rows with missingTitle                             |  1 row removed       
Text Standardization  |  Standardized case and spacing forType,Country,Duration     |  Completed           
Date Format           |  Converted all dates to formatdd-mm-yyyy                    |  Completed           
Column Headers        |  Renamed to lowercase and replaced spaces with underscores  |  Completed           
Data Types            |  Ensured all fields have consistent text and date formats   |  Completed   


Cleaned Dataset (Preview)-

title         |  type     |  country        |  release_date  |  age   |  duration   
--------------+-----------+-----------------+----------------+--------+-------------
Breaking Bad  |  tv show  |  United States  |  29-09-2013    |  18+   |  62 episodes
Money Heist   |  tv show  |  Spain          |  NaN           |  16+   |  41 episodes
Dark          |  tv show  |  Germany        |  NaN           |  None  |  26 episodes
Breaking Bad  |  tv show  |  United States  |  NaN           |  18+   |  62 episodes
