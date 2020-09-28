# goexample

Install mysql

Create a database called `goblog` and table called `Employee` in it.

```mysql
CREATE DATABASE goblog;
USE goblog;
DROP TABLE IF EXISTS `Employee`;
CREATE TABLE `Employee` (   `id` int(6) unsigned NOT NULL AUTO_INCREMENT,   `name` varchar(30) NOT NULL,   `city` varchar(30) NOT NULL,   PRIMARY KEY (`id`) ) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;
```

Reference : https://www.golangprograms.com/example-of-golang-crud-using-mysql-from-scratch.html
