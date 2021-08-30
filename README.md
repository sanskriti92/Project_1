# P1_MoviesData_Analysis
## Project Description
This project aims to analyse movielens dataset by using Apache Hive .

## Technologies Used
Apache Hive - version 2.1.1
- Hortonworks Data Paltform - version 2.6.5
- Apache Hive - version 2.1.1

# Features
## List of features
This project analyzes the movies data to get the

movies of specific genre.
movies which got most ratings.
top rated movies.
low rated movies, and many more.

#To-do list:
Solving queries by giving hive commands.

#Getting Started
Clone the project
$ git clone https://github.com/atulgandhi1137/P1_MoviesData_Analysis.git

#Prerequisite
A Hadoop ecosystem
-Apache Hadoop should be installed with all the components.

#Usage
After logging into VM, clone the project onto local machine and unzip all the csv files.
Then, copy csv files from local to hdfs.
$ hdfs dfs -put ./filename /<hdfs path>
You can use hive using either hive shell or hive view. (Type hive to start hive shell)
Upload the data from all the csv files to the respective tables from Hive View->Upload Table
Then, start executing queries.
