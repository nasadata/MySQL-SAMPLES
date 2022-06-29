# MySQL-SAMPLES

MySQL Workbench 8 version 8.0.29 

To run test:  

SELECT SUM(CASE WHEN variable IS NULL THEN 1 ELSE 0 END) 

	     AS column_null_volume, COUNT(variable) AS Volume_count_not_null 
       
FROM table
 

Results sample view:  

column_null_volume  Volume_count_not_null 

0			              3555 

Space modification made to run on MySQL from PostgreSQL.  

 

Test Files 

Data exploration brings challenges with every piece of data. Preserving the integrity of the data used for
analysis, confirmation is never too much. When using different distributions of SQL and spreadsheets it is
essential to compare results. Data from point “a” to point “b” and make sure numbers are accurate. 

Change the word variable on the code (two times) for the variable on your table,change the word table for
the name of your data source or table name.

Compare the results with the source. 

Note: MySQL results can deliver 0 on Null numbers if the value of the cell equals 0. 

Please see the next repository for MySQL query to find hide null values.
