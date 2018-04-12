# Exercise 1
Connect to the MySQL database on the cluster using Sqoop and import all of the data from the customer table into HDFS.

Data Description
A MySQL instance is running on the gateway node. In that instance, you will find a table that constains twenty-five million rows of customer data.

MySQL database information:
-Installation: On the cluster node gateway
-Database name: problem1
-Table name: customer
-Username: cloudera
-Password: cloudera

Output Requirements
-Place the customer files in the HDFS directory
	/user/cert/problem1/solution/
-Use a text form with  comma as the columnar delimiter
-Load every customer record completely
