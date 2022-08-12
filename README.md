# Movies-ETL
## Overview and Description of Project
In this project, the extract, transform, and load (ETL) process was implemented using large datasets in the form of two csv files and one json file containing data regarding movies. The JSON file contains wikipedia movie data including budgets, box office returns, cast and crew, production and distribution, and more. One of the csv files contains movie ratings data from MovieLens, a site run by the GroupLens research team. The other csv file contains metadata providing more details on the movies from kaggle.com. <br/><br/>
The purpose of this project was to create an automated pipeline that used a function that accepts these files and completes the ETL process. Also, the function is designed such that any updates to the datasets can be inputted into a database. The function will perform file imports into dataframes using the Pandas library, data cleaning, formatting, adjusting of data types, alteration of data columns, merging of dataframes, and imports into a SQL database, where further analysis can be performed.<br/><br/>
### Technologies and skills used in this project:
* Python Pandas library
* Python Numpy library
* Extract, transform, and load (ETL) process
* Python functions
* Python regular expressions
* SQL
* SQLAlchemy