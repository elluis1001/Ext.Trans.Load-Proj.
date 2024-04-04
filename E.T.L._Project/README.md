# Crowdfunding ETL Project

By:  Beauty Simora and Luis R. Rivera Jr.

## Project Overview
In this project, I performed an ETL (Extract, Transform, Load) process on crowdfunding data. The main objective was to extract and transform data from Excel files into a format suitable for a PostgreSQL database, create a database schema, and load the transformed data into the database.

## Project Completion
I am pleased to report that I have successfully completed the Crowdfunding ETL project. The project involved the following key steps:

1. **Created the Category and Subcategory DataFrames**: I extracted and transformed data from the `crowdfunding.xlsx` Excel file to create two DataFrames: `category` and `subcategory`. The `category` DataFrame contains unique category IDs and names, while the `subcategory` DataFrame contains unique subcategory IDs and names.

2. **Created the Campaign DataFrame**: I extracted and transformed data from the `crowdfunding.xlsx` Excel file to create the `campaign` DataFrame. This DataFrame contains information about each crowdfunding campaign, including the campaign ID, contact ID, company name, description, goal, pledged amount, outcome, backers count, country, currency, launch date, end date, and associated category and subcategory IDs.

3. **Created the Contacts DataFrame**: I extracted and transformed data from the `contacts.xlsx` Excel file to create the `contacts` DataFrame. This DataFrame contains information about each contact, including the contact ID, first name, last name, and email address. I used either Python dictionary methods or regular expressions to extract and transform the data.

4. **Created the Crowdfunding Database**: I designed an Entity Relationship Diagram (ERD) for the crowdfunding database using QuickDBD. Based on the ERD, I created a table schema for each CSV file, specifying the data types, primary keys, foreign keys, and other constraints. I then created a new PostgreSQL database named `crowdfunding_db` and created the tables using the schema. Finally, I imported each CSV file into its corresponding SQL table and verified the data integrity.

## Repository Contents
This repository contains the following files:

- `category.csv`: CSV file containing the category data
- `subcategory.csv`: CSV file containing the subcategory data
- `campaign.csv`: CSV file containing the campaign data
- `contacts.csv`: CSV file containing the contact data
- `crowdfunding_db_schema.sql`: SQL file containing the database schema
- `README.md`: This readme file providing an overview of the project and its completion

## Conclusion
The completion of this project demonstrates my ability to perform ETL processes, work with Excel data, create DataFrames using Python and Pandas, design database schemas, and interact with PostgreSQL databases. The transformed data and database created in this project can be used for further analysis and insights into crowdfunding campaigns and contacts.
