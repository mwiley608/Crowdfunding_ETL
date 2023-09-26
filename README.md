# Crowdfunding_ETL
Bootcamp Project 2
The files contained in the Crowdfunding_ETL repository were created as an educational bootcamp project to build an ETL pipeline using Python and Pandas, as well as extract and transform data collected about crowdfunding campaigns. Using the script in the ETL_Mini_Project ipynb file, the crowdfunding and contacts Excel files located in the Resources folder were transformed into four separate datasets referencing the category data, subcategory data, individual campaign data, and the contact data. The transformed datasets were exported as CSV files and were then used to create an ERD, table schema, and Postgres database. The QuickDBD script and a png of the resulting ERD can be found in the Resources file, along with the four CSV files. The Postgres script used to create the database in pgAdmin is the crowdfunding_db_schema.sql file. There is also a sql_table_queries.sql file to show the SELECT statements used to verify the data was correctly imported into the tables. 

References: 
The fictional data used in this project was created by edEx Boot Camps LLC for educational purposes only.

The file contained in the Starter_Files folder was used as a starting point for the Jupyter Notebook file.

The website: https://app.quickdatabasediagrams.com/#/ was used to build the ERD and export the png and script to create the tables in pgAdmin.
The website: https://stackoverflow.com/questions/37333299/splitting-a-pandas-dataframe-column-by-delimiter was used to review how to split data into two new columns while retaining the original.

The website: https://saturncloud.io/blog/how-to-change-multiple-columns-in-pandas-dataframe-to-datetime/#:~:text=To%20convert%20multiple%20columns%20in,values%20using%20the%20format%20parameter was referenced to update multiple datatypes to DATE at one time. 

A tutor assisted with creating the Contacts DataFrame.  

Collaborators: katyphillips, mtguadamuzruth, mwiley608

