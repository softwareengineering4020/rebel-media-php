Uploading dbrebelmedia database

Using PHP, MySQL,and Apache:

Make sure to download & install phpMyAdmin:  
https://www.phpmyadmin.net/

-------------------------------------------------------------------------------------------------------------------------------
*Once logged into mysql, redirect to the following url: 

localhost/phpmyadmin

*Log into phpmyadmin (with same credentials as mysql).

Then click on Databases tab. Create database name -> dbrebelmedia (Collation) Create

Select the newly created database (see table with database name), click on dbrebelmedia

Once you're inside database (you should see the following on the top: Server 127.0.0.1 Database: dbrebelmedia)
Click on Import tab. Choose File (Make sure you have downloaded dbrebelmedia.sql file), selected dbrebelmedia.sql file.
*Don't change any other settings.
Then clicl Go.

You should received message success ("Import has been successfully finished, 41 (num of queries - this num might change once file is updated) queries executed. (dbrebelmedia.sql).

--------------------------------------------------------------------------------------------------------------------------------------
Then if you want to add yourself to the admin table, do as follows:

On the left hand panel select 'admin' table. Then click on Insert tab.
Type your name, email, and password into the big text boxes (you don't need to select anything else).
Then click on Go.
You should received the following message: 1 row inserted (Inserted row id: 7).

Then after SQL query has been created (which you should see below in the white textbox as INSERT INTO command) click Go.
