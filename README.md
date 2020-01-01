# mysql

`$ sudo mysql`

`mysql> SELECT user,authentication_string,plugin,host FROM mysql.user;`

`ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '1234';`

`FLUSH PRIVILEGES;`

`mysql> exit`

`$ sudo mysql`

`$ mysql -u root -p`

### References

<https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-18-04>
