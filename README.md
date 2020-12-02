
# Simple Login System ![php](https://img.shields.io/badge/php-hypertext%20preprocessor-blueviolet?style=for-the-badge&logo=php&logoColor=white)
#### Created using Apache, MySQL, and PHP.

###### To use this, first we will need to create a database. I recommend using PHPMyAdmin for this. You will also need an Apache or Nginx webserver, PHP 5.0.0 or higher, and you will need a MySQL or MariaDB database.

1. Login into your database and set up a new database called "loginsystem" this step is very important for a few reasons. You are setting up the database where all the users login information goes, and it needs to be called that because that's the name of the database that the various HTML and PHP files will be looking for. However, if you really want to change the name of the database for whatever reason then feel free to edit the files.

2. After you've done that, you will want to create a new table inside of the database. I already did all the work for you so all you should have to do is copy and paste the lines of code below into the SQL section of PHPMyAdmin or just pop it into the terminal with your database server. Either way should work just fine.

```
CREATE TABLE users (
  user_id int(11) not null AUTO_INCREMENT PRIMARY KEY,
  user_first varchar(256) not null,
  user_last varchar(256) not null,
  user_email varchar(256) not null,
  user_uid varchar(256) not null,
  user_pwd varchar(256) not null
);
```

![You can space it out if you want, it works without it.](https://i.imgur.com/1olPDe9.png)


3. Once you do that, hit go. What you just did is told the database to create a table called 'users' that has data in it with user information.

4. Now go to your URL where the server is located and signup

#### I don't care how you use this system, you can use it for your own website if you want or you can completely change everything, totally up to you. I hope this README file was helpful to you. Have fun!
