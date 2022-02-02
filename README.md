# Movies-ETL

Purpose
The purpose of this study was to learn the data pipeline process Extract, Transform and Load. The process was broken down into several steps:

Extracting data from disparate resources using Python
Cleaning and transforming the data using Pandas
Using regular expressions to parse data and transform text into numbers
Loading data with PostgreSQL
One part of the data was initially provided, which is Wikipedia movies .json file. The rest of data was downloaded in archive from Kaggle, containing movie dataset with various information.

Cleaning the data contained looping through the data sets and removing the unnecessary columns using list comprehensions, changing the data types of the info in columns and using regular expressions to parse the rest of the data.

Two tables of cleaned and ready-to-use data was loaded into PostgreSQL database using pgAdmin.
