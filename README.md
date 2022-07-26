<b>Project: Data Modeling with Cassandra</b>

<b>Introduction:</b>
    
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. There is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app. My role is to create an Apache Cassandra database which can create queries on song play data to answer the questions.

<b>Project Overview:</b>

In this project, I would be applying Data Modeling with Apache Cassandra and complete an ETL pipeline using Python. I am provided with part of the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

<b>Datasets:</b>

For this project, you'll be working with one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv


<b>Files:</b>

<b>Project_2_NOSQL.ipynb:</b> This is the final file provided in which all the queries have been written with importing the files, generating a new csv file and loading all csv files into one. All verifying the results whether all tables had been loaded accordingly as per requirement

<b>Event_datafile_new.csv:</b> This is the final combination of all the files which are in the folder event_data

<b>Event_Data Folder:</b> Each event file is present separately, so all the files would be combined into one into event_datafile_new.csv
