<!-- My Sql instalation -->

To install MySql Server ```sudo apt install mysql-server```
To start MySql cmd ```sudo mysql```

<!-- Authentication Methiod -->

To set  Root User ```alter user 'root'@'localhost' identified with mysql_native_password by 'Your Password'     ```
type ```exit``` to exi the mysql cmd

For Secure installation validate Passsword Component ```mysql_secure_installation``` this will ask to enter root password. 
setup passwrd strenght standards 
typr yes for all configurations for more security

Now the Mysql cmd is Secure so to open that follow this
```mysql -u root -p```

After entering passwod you can run queries in mysql
To Create database ``` create database DBname```

To show all the DB ```show schemas``

To create Users for DB ```create user 'username'@'localhost' identified with mysql_native_password by 'userPassword'```

To select database ```use DBname```

To list user **you must be in mysql DB** and than run this query to see all the users ```select user from user```

Providing Previledges to new user ```grant all on DBname.* to 'userName'@'localhost' ```

To see the Mysql in PHPMyAdmin we have to install PHP ```sudo apt install php``` 
and after this install php my admin ```sudo apt install phpmyadmin```

after that you will se a screen to select server **chose Apache is recommended**
select server than press **space bar key**

that will auto  install the server and dependencies

It will ask to configure Server by yourself So you ca choose no if you want default primary auto setup configuration

**Congratulation Your server setup is done for mysql phpmyadmin**

enter the ip address in browser to see that.  you will enter local host if you are accesing the server whithin your local server
Enter Credentials and you are good to go 