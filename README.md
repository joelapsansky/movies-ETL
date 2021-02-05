# Movies-ETL
After refactoring code from the modules, I wrote one function requiring 3 parameters:  
* Movies JSON file from Wikipedia  
* Movies metadata CSV file from Kaggle  
* Ratings CSV file from Kaggle  
  
Before doing anything, I sourced these files from the web and saved them in a repository folder.  From there, I was able to transform (drop, clean, parse, merge, etc.) and load data using functions.  
  
Finally, I loaded this particular data frame to two separate tables in pgAdmin.  The final ETL function is in this finished file: [ETL Create Database](/ETL_create_database.ipynb)
## SQL Counts
![Movies Query](/Resources/movies_query.png "Movies Query")  
![Ratings Query](/Resources/ratings_query.png "Ratings Query")
