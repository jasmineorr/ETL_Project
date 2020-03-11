# ETL_Project
ETL Project

* Our Group Name: Jet Team
* GITHUB REPO: https://github.com/jasmineorr/ETL_Project
* We've pulled 2 data sets - one on H1N1 and one on the Coronavirus. We'll combine the 2 data sets to look 
  at the impact of each across various countries. 
* Jasmine Orr
* Victor Ime

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
2. Collect the datasets and import the csv files into dataframes.
3. Pull desired columns from the dataframe to create new dataframes.
4. Rename columns.
5. Clean the data by combining duplicate country names and data. Assign index to dataframes.
6. Use groupby, sum & sortby to wrangle data and create two dataframes with the same format.
7. Create the database connection and confirm the tables in the database
8. Load the dataframes into database
9. Create tables in pgAdmin and a primary key for both tables
10. Select all information from tables to confirm data loaded and can begin queries when necessary

Analysis on corona virus and Swine Virus ranking parameters Retrieving the dataset from the source kaggle.com i. Downloaded the latest(2019) coronavirus.csv from data.kaggle.com

ii. Uploaded the dataset on to the resource folder "Resources/2019_nCoV_data.csv"

iii. Read the file and create a dataframe to provide a structured data with rows and columns.

iv. Use the .copy() to return a shallow copy of the list, hence droping some columns and picking the necessary columns.

Cleaning of the dataset: The columns in the consolidated dataset that had similar country name was groupby to have it in a single column. Sort out the data set via ascending then re-index the sorted dataset. Use the .astype funtion to provide capability to convert suitable existing column to categorical type. Connect project work to pgAdmin with a line of code Grab data from ETL_project and upload to DB Use pandas to load json converted DataFrame into database Confirm data has been added by querying the table created on pgAdmin