# PHP MySQL User Login SignUp API

This offer's step by step tutorial that will guide you to setup up Login + Signup API using Core PHP + MySQL following best practices with folders structure.

It will guide you to create very simple Login & Signup Restful Webservices using PHP, without using any Framework or Library.

File Structure
We’ll use this folders & files structure for writing our Webservice.

api
├─── config/
├────── database.php – file used for connecting to the database.
├─── objects/
├────── user.php – contains properties and methods for “user” database queries.
├─── User/
├────── signup.php – file that will accept user data to be saved to the DB.
├────── login.php – file that will accept username & password and validate



HOW TO RUN:

I’m using XAMPP so I’m going to paste the “api” folder in the htdocs folder of XAMPP.

Remember that Signup API accepting POST parameters and Login API accepting GET.

Now you can test your Signup API using this URL => http://localhost/api/users/signup.php with Post parameters of username, & password

and for login

http://localhost/api/users/login.php?username=shehryar&password=12345


NOTE:

Note: For keeping thing simple for Beginners I’m storing the plain password in Database which is not a good practice. Password must be hashed using PHP hashing methods.