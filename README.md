DataModelingUsingCassandra
Build an ETL pipeline using Python and design a non-relational database using Cassandra

Learning Objective:

To Build database using quick design techniques in Cassandra.
To Improve existing model using a query driven methodology in Cassandra.
To Optimize Existing model via analysis and validation techniques in Cassandra.

Project Template
To get started with the project, go to the workspace on the next page, where you'll find the project template (a Jupyter notebook file). You can work on your project and submit your work through this workspace.

The project template includes one Jupyter Notebook file, in which:

you will process the event_datafile_new.csv dataset to create a denormalized dataset
you will model the data tables keeping in mind the queries you need to run
you have been provided queries that you will need to model your data tables for
you will load the data into tables you create in Apache Cassandra and run your queries
Project Steps
Below are steps you can follow to complete each component of this project.

Modeling your NoSQL database or Apache Cassandra database
Design tables to answer the queries outlined in the project template
Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
Develop your CREATE statement for each of the tables to address each question
Load the data with INSERT statement for each of the tables
Include IF NOT EXISTS clauses in your CREATE statements to create tables only if the tables do not already exist. We recommend you also include DROP TABLE statement for each table, this way you can run drop and create tables whenever you want to reset your database and test your ETL pipeline
Test by running the proper select statements with the correct WHERE clause
Build ETL Pipeline
Implement the logic in section Part I of the notebook template to iterate through each event file in event_data to process and create a new CSV file in Python
Make necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in your data model
Test by running SELECT statements after running the queries on your database


Data Modeling
Student creates the correct Apache Cassandra tables for each of the three queries. The CREATE TABLE statement should include the appropriate table.

Student demonstrates good understanding of data modeling by generating correct SELECT statements to generate the result being asked for in the question.

The SELECT statement should NOT use ALLOW FILTERING to generate the results.

Student should use table names that reflect the query and the result it will generate. Table names should include alphanumeric characters and underscores, and table names must start with a letter.

The sequence in which columns appear should reflect how the data is partitioned and the order of the data within the partitions.

PRIMARY KEYS
The combination of the PARTITION KEY alone or with the addition of CLUSTERING COLUMNS should be used appropriately to uniquely identify each row.
