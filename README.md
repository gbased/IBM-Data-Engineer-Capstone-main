# IBM_Data_Engineer_Capstone-
Final project of the IBM Data Engineer course
![image](https://github.com/gbased/IBM_Data_Engineer_Capstone-main/assets/139152629/facff608-ca58-46c1-9eb6-19197653657e)

Tools and Technologies:
OLTP database - MySQL
Production Data warehouse – DB2 on Cloud
Staging - Data warehouse – PostgreSQL
Business Intelligence Dashboard - IBM Cognos Analytics
Process:
SoftCart's online presence is primarily through its website, which customers access using a variety of devices like laptops, mobiles and tablets.

All the catalog data of the products and transactional data like inventory and sales are stored in the MySQL database server.

SoftCart's webserver is driven entirely by this database.

Data is periodically extracted from this database and put into the staging data warehouse running on PostgreSQL.

Production data warehouse is on the cloud instance of IBM DB2 server.

BI teams connect to the IBM DB2 for operational dashboard creation. IBM Cognos Analytics is used to create dashboards.

An ETL process using a shell script is set up to extract new transactional data for each day from the OLTP database and load it into the staging data warehouse.
