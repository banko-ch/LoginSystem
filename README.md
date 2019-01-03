
# Simple Login System
#### Created using Apache, MySQL, and PHP.

###### To use this, first we will need to create a databasse inside PHPMyAdmin (assuming you have already setup a web server with the latest versions of Apache, PHP, and MySQL)

1. Login into PHP MyAdmin and set up a new database called "loginsystem" this step is very important for a few reasons. You are setting up the database where all the users login information goes, and it needs to be called that because that's the name of the database that the various HTML and PHP files will be looking for. However, if you really want to change the name of the database for whatever reason then feel free to edit the files.
2. After you've done that, go into the database and click on the SQL and in the editor type these few lines of code 
```CREATE TABLE users (
user_id int(11) not null AUTO_INCREMENT PRIMARY KEY,
user_first varchar(256) not null,
user_last varchar(256) not null,
user_email varchar(256) not null,
user_uid varchar(256) not null,
user_pwd varchar(256) not null
);
```
![You can space it out if you want, it works without it.](http://yursite.cf/quizwiz.png)
3. Once you do that, hit go. What you just did is told the database to create a table called 'users' that has data in it with user information.

4. Now go to your URL where the server is located and signup

#### I do not care how you use this system, you can use it for your own website if you want, or you can completely change everything. I how this readme file was helpful to use. Have fun!
