# Data Analysis Project for a DVD Rental Business

<img src="https://github.com/user-attachments/assets/1db0cedd-1800-4413-8ff1-b2294c85450b" width="300" />

<strong>Photo Source: Camille Cohen</strong>


I completed this project during my 5th semester at WGU as a part of the class, Advanced Data Management, D326.

For this project, I performed a comprehensive data analysis using the postgresqls sample dataset, “dvdrental”. I began by identifying a real-world business question and then designed a report comprising a detailed table for granular data and a summary table for aggregated insights. I chose the following business question for this report:  Which top three film categories had the most rentals each month? I wrote SQL queries to create these tables, selecting specific fields from relevant dataset tables and incorporating a custom transformation using a user-defined function to enhance data readability. I implemented triggers to automatically update the summary table as data was added to the detailed table and created stored procedures to refresh both tables by clearing and reloading them from raw data. 

For the complete project requirements, please refer to the “Task Overview.pdf” file.  

For my complete project report, refer to “Task PA.pdf”.

Scroll down to the bottom of the page for instructions to execute the queries from “code.txt”.

Below is an image of the summary table. The summary table includes total_monthly_rentals - this is the sum of all rental transactions for a given month and a given film category.

![1](https://github.com/user-attachments/assets/107cab2a-fa08-44f5-90be-c7ad272f8c67)

<strong>Instructions to Execute SQL Queries from “code.txt” in pgAdmin 4:</strong>

1.	Download and Extract the DVD Rental Database:<br>
o	Download the DVD rental database: https://neon.tech/postgresql/postgresql-getting-started/postgresql-sample-database<br>
o	Extract the file to access the .sql script or the dataset.<br>
2.	Open pgAdmin 4:<br>
o	Launch the pgAdmin 4 application on your system.<br>
3.	Connect to Your PostgreSQL Server:<br>
o	In the Browser Panel (Object Explorer) on the left, expand Servers.<br>
o	If your server is not already connected, right-click on your server (e.g., PostgreSQL 13) and select Connect Server.<br>
o	Provide the necessary credentials if prompted.<br>
4.	Restore the DVD Rental Database:<br>
o	If the dvdrental database is not already available, you need to restore it:<br>
- Right-click Databases under your server and select Create > Database. Name it dvdrental and click Save.<br>
- Right-click on the newly created dvdrental database, select Restore, and upload the extracted .sql file to restore the database.<br>
5.	Open the Query Tool:<br>
o	In the Browser Panel, navigate to Servers > PostgreSQL 13 > Databases > dvdrental.<br>
o	Right-click on dvdrental and select Query Tool.<br>
6.	Execute SQL Code:<br>
o	Open the code.txt file.<br>
o	Copy and paste your desired SQL code into the Query Tool editor.<br>
7.	Run the SQL Code:<br>
o	Click the "Execute/Run" button (lightning icon) in the toolbar to execute the SQL code.<br>
8.	View Results:<br>
o	The results of your query will appear in the lower panel of the Query Tool.<br>


