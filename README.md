# login-springboot-mysql-project

Connected to MySQL database and Docker.
Uses Maildev and Postman.

While there are still some features to be added, the program is working as it is.  

To run:

install MailDev: https://www.npmjs.com/package/maildev

Then -> click on run.  

Fill in your data in Postman and POST it to localhost:8080/api/v1/registration 

{
    "firstName": "",
    "lastName": "",
    "email": "",
    "password": ""
}

Open Maildev and click on link to validate your email. 

Open localhost:8080 and log in using the data.  

