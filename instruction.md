# delcibo_database_server

Создать имя пользователя</br>
```
  apt-get install mysql-server
  mysql
  CREATE USER 'user'@'localhost' IDENTIFIED BY 'pswrd';
  GRANT ALL PRIVILEGES ON * . * TO 'user'@'localhost';
  FLUSH PRIVILEGES;
  CREATE DATABASE db;
    #редактируем файл 
  sudo nano /etc/mysql/mysql.conf.d/mysqld.cnf
  bind-address=0.0.0.0
  sudo service mysql restart

  
```
