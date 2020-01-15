CRUD functionality in nodejs, express (database MYSQL)

Node.js CRUD application based on the mysql database design and Express.js framework

Install express, mysql and bodyparser

npm install --save express mysql body-parser
Creating database and table

create database test;

use test;

CREATE TABLE users (
id int(11) NOT NULL auto_increment,
name varchar(100) NOT NULL,
age int(3) NOT NULL,
email varchar(100) NOT NULL,
PRIMARY KEY (id)
);



