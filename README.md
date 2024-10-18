# Crowdfunding_ETL
Project 2 

Project overview:
For this ETL mini project, the team partnered to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After we transformed the data, we created four CSV files and use the CSV file data to create an ERD and a table schema. Finally, we uploaded the CSV file data into a Postgres database.

The instructions for this mini project are divided into the following subsections:

Create the Category and Subcategory DataFrames
Create the Campaign DataFrame
Create the Contacts DataFrame
Create the Crowdfunding Database

*************************************************************************************************************************************************************************************************

Description of files in Github repository:

ETL_Mini_Project_MAbdulkarim_TSullivan_RRoehl.ipynb - Jupyter notebook that contains the analysis for the project.  Extract and analyze crowdfunding and campaign data.  Create and export category and subcategory csv files.  Merge categorical data with campaign data and export to campaign.csv file.  Clean and extract contacts data and export to contacts.csv file.

crowdfunding_db_schema_image.png - Shows the ERD diagram for the Crowdfunding database schema.  Image generated from quickdatabasediagrams.com.

crowdfunding_db_schema_1_tables.sql - SQL statements used to create the tables as described in the Crowdfunding database schema.

crowdfunding_db_schema_2_inserts.sql - SQL statements used to insert data into the tables created.

crowdfunding_db_schema_3_selects.sql - SQL select statements to test and verify the newly created tables and imported data.

Resources (folder) - Contains contacts.xlsx and crowdfunding.xlsx files that are used as datasources for the project.  Folder also contains exports generated from the Jupyter notebook including:  campaign.csv, category.csv, contacts.csv, and subcategory.csv.



