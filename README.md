# OOPLR
Object oriented login system in PHP
In MySQL create a database
Create groups table with fields:
id int(11) primary key auto increment
name varchar(20)
permissions text

Insert Value for groups table

name:Standard User
name: Admin, permissions: {"admin":1}

Create users_session table with fields
id int(11) primary key auto increment
user_id int(11)
hash varchar(64)

Create users table with fields
id int(11) primary key auto increment
username varchar(20)
password varchar(64)
salt varchar(32)
name varchar(50)
joined datetime
group int(11)




In core/init.php set your MySQL credentials and database name;

