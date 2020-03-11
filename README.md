# ETL_Project

ETLProject
Second Group project for Data Bootcamp, Gatech - by Jasmine, Victor and, Jerome

Project Title - Data integration for data analysis and management

Team Members
Jasmine Orr, Victor Ime, Jerome Pelham.

Project Description
The scope of our project is to integrate two data set for the purpose of analyzes and management of outbreaks and it impact in various countries.

Research Questions to Answer
o	What is the number of impact in America and Europe.
o	What is the number of death

Datasets to be Used
Two datasets from Kaggle.com.


Rough Breakdown of the tasks
1. Define the Goal and questions for the Project
2. Collect the data – Pull the csv files, online datasets.
3. Filter the dataframe created to specific columns then rename is necessary.
4. Clean the data by dropping and setting and setting the index
5. Rename the column header, then set the index
6. Create the database connection, the confirm the tables
7. Load the data frame into database
8. Create a table on pgAdmin and a primary key for both table
9. Select the tables and join to populate the table on pgAdmin


Analysis on corona virus and Swine Virus ranking parameters
Retrieving the dataset from the source kaggle.com
i. Downloaded the latest(2019) coronavirus.csv from data.kaggle.com

ii. Uploaded the dataset on to the resource folder "Resources/2019_nCoV_data.csv"

iii. Read the file and create a dataframe to provide a structured data with rows and columns.

iv. Use the .copy() to return a shallow copy of the list, hence droping some columns and picking the necessary columns.

Cleaning of the dataset:
The columns in the consolidated dataset that had similar country name was groupby to have it in a single column.
Sort out the data set via ascending then re-index the sorted dataset.
Use the .astype funtion to provide capability to convert suitable existing column to categorical type.
Connect project work to pgAdmin with a line of code
Grab data from ETL_project and upload to DB
Use pandas to load json converted DataFrame into database
Confirm data has been added by querying the table created on pgAdmin