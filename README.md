# NeoStats-SQL-Assessment

A. SQL Environment Set-Up
1. Install postgres sql from https://www.enterprisedb.com/downloads/postgres-postgresqldownloads.
1.1 use default settings to install
1.2 It will prompt for a password. Give a password of your choice and remember it for rest of the
execution.
1.3 In the last step Untick the Stack Builder and close.

2. Update env variable PATH and add 'C:\Program Files\PostgreSQL\15\bin'
2.1 Type env in start menu and select Edit the system environment variable
2.2 Select Environment Variables; a new window will popup
2.3 Select 'Path' -> Edit -> New -> paste the above given path and select Ok

3. Open cmd prompt and typed 'psql -U postgres'. This starts the postgres prompt.

4. Write SQL queries to answer following questions:

a. Find Top 10 customers by total spend in the year 2005 and 2006.

b. Find the total number of orders and average order value by area code and year.

c. Find the total number of orders where receipt number is missing.

d. Find the total number of orders and average order value by payment method where
order type is Gift

e. Find the total number of orders and average order value for customers in the age range
31-40 and with store distance less than 10 miles
