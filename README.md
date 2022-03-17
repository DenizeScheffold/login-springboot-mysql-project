# login-springboot-mysql-project

Connected to MySQL database and Docker.
Uses Maildev and Postman.

While there are still some features to be added, the program is working as it is. 


To run with MailDev:

Install MailDev: https://www.npmjs.com/package/maildev

Connect to your MySQL.

Run in IDE: click on run.  

Create account: Fill in your data in Postman and POST it to localhost:8080/api/v1/registration 

{
    "firstName": "",
    "lastName": "",
    "email": "",
    "password": ""
}

To validate email: Open Maildev and click on link. 

Log in: Open localhost:8080 and use the data you put in to Postman.


-------------------------------


To run without MailDev:

Connect to your MySQL.

Run in IDE: click on run.  

Fill in your data in Postman and POST it to localhost:8080/api/v1/registration 

{
    "firstName": "",
    "lastName": "",
    "email": "",
    "password": ""
}


To validate email: use the generated token (found with SQL in the database) and use it as follow: 
http://localhost:8080/api/v1/registration/confirm?token=" + token 

Log in: Open localhost:8080 and use the data you put in to Postman.

