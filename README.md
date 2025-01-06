# Data Analysis Project for a DVD Rental Business

I completed this project during my 5th semester at WGU as a part of the class, Advanced Data Management, D326.

For this project, I performed a comprehensive data analysis using the postgresqls sample dataset, “dvdrental”. I began by identifying a real-world business question and then designed a report comprising a detailed table for granular data and a summary table for aggregated insights. I chose the following business question for this report:  Which top three film categories had the most rentals each month? I wrote SQL queries to create these tables, selecting specific fields from relevant dataset tables and incorporating a custom transformation using a user-defined function to enhance data readability. I implemented triggers to automatically update the summary table as data was added to the detailed table and created stored procedures to refresh both tables by clearing and reloading them from raw data. 

For the complete project requirements, please refer to the “Task Overview.pdf” file.  

For my complete project report, refer to “Task PA.pdf”.

Instructions to Execute SQL Queries from “code.txt” in pgAdmin 4:

1.	Download and Extract the DVD Rental Database:
o	Download the DVD rental database from Neon Tech's sample database.
o	Extract the file to access the .sql script or the dataset.
2.	Open pgAdmin 4:
o	Launch the pgAdmin 4 application on your system.
3.	Connect to Your PostgreSQL Server:
o	In the Browser Panel (Object Explorer) on the left, expand Servers.
o	If your server is not already connected, right-click on your server (e.g., PostgreSQL 13) and select Connect Server.
o	Provide the necessary credentials if prompted.
4.	Restore the DVD Rental Database:
o	If the dvdrental database is not already available, you need to restore it:
	Right-click Databases under your server and select Create > Database. Name it dvdrental and click Save.
	Right-click on the newly created dvdrental database, select Restore, and upload the extracted .sql file to restore the database.
5.	Open the Query Tool:
o	In the Browser Panel, navigate to Servers > PostgreSQL 13 > Databases > dvdrental.
o	Right-click on dvdrental and select Query Tool.
6.	Execute SQL Code:
o	Open the code.txt file.
o	Copy and paste your desired SQL code into the Query Tool editor.
7.	Run the SQL Code:
o	Click the "Execute/Run" button (lightning icon) in the toolbar to execute the SQL code.
8.	View Results:
o	The results of your query will appear in the lower panel of the Query Tool.


