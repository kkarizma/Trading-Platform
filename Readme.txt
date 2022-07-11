Trading Platform - ReadMe


To develop the database aspect of a platform where people can sell and buy stocks and other derivatives where they can state their own price and information of individual and total stocks is maintained. 
	Build Status
	We have created multiple procedures in SQL for various functionalities such as registering a new user in the database, buying and selling stocks, increasing the balance of the user account and displaying stock information available in the database. Concurrency has been achieved by taking queries and executing them atomically through transactions. Unique Customer_id generated and displayed on user registration should be remembered by the user for performing any further monetary transactions in our trading platform.
	Code Style
	We have created multiple procedures in SQL for various functionalities such as registering a new user in the database, buying and selling stocks, increasing the balance of the user account and displaying stock information available in the database. These procedures can be called with valid parameter values passed.
	Version used
	The entire file is created and tested in SQL using MySQL workbench version 8.0.28
	



Instructions for execution
1. The following SQL queries can be executed together. There is no need to execute them one at a time.
1. Create database
2. Use database
3. Create tables
4. Create procedures
5. Insert data in tables


2) The DML queries which are calling some procedure, are recommended to be executed one at a time in the specific order given in the sql file, so that one can observe the modifications made to the database and the functionalities of the respective procedures.


Limitations
One limitation in our procedures is that the user password check is not case-sensitive in the current form of our project as SQL is not case-sensitive.