# Data-Analyzer-and-Visualizer

a web application that can dynamically extract, transform, & load data from source to target data layer.

Step 1:
Select Format:

1. If you have selected the MySQL Database option then UI should ask username & password and the IP address will be your local host . 

2. If you have selected the CSV option then it helps in browsing the CSV file  and it should be able to load csv into the MySQL database.


Step 2:
Select Source:
1. If you have selected MySQL Database then it can display all the databases in the MySQL Database. If you click on the Database Name it will show Tables in the respective database. If you click on the table it will show columns in the respective tables where you can select the fields you want to transform as well as the primary key.


Step 3:
 Visualizer:

1. Table1 & Table2 (from MySQL) are the two tables that you have generated by selecting the fields from both tables.

2. After generating tables Table1 & Table2 you can apply join transformation (logic can be simple SQL query) in which you will trigger the join query that takes Table1 & Table2 and parameters (common column name & join type) as input which will be passed by the SQL query to be executed on both the tables Table1 & Table2.

3. After applying the join transformation you can apply sort transformation (logic can be simple SQL query) on the data that has been generated after applying the join transformation in which you will trigger the sort query that takes output of join query and parameters (column name & sorting type) as input which will be passed by the SQL query to be executed on both the table generated by join transformation.

4. In the select output file type you have to implement a functionality which can save the result of sort query as CSV & as a table in MySQL.

