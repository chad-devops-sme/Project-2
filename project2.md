# WEB STACK IMPLEMENTATION (LEMP STACK) ON AWS

## STEP 1 – INSTALLING THE NGINX WEB SERVER

sudo apt update

![apt update](Images/sudo-apt-update-nginx.jpg)


sudo apt install nginx

![apt install](Images/sudo-apt-install-nginx.jpg)


sudo systemctl status nginx

![sudo systemctl](Images/sudo-systemctl-status-nginx.jpg)

TCP 80

![tcp 80](Images/tcp-80.jpg)

Nginx Page

![nginx page](Images/nginx-page.jpg)




# STEP 2 — INSTALLING MYSQL

sudo apt install mysql-server

![apt install](Images/sudo-apt-install-mysql-server.jpg)




sudo mysql 

![mysql](Images/sudo-mysql.jpg)



sudo mysql_secure_installation

![mysql_secure_installation](Images/sudo-mysql_secure_installation.jpg)

sudo mysql -p

![mysql -p](Images/sudo-mysql-p.jpg)


# STEP 3 – INSTALLING PHP 


sudo apt install php-fpm php-mysql

![apt install](Images/sudo-apt-install-php.jpg)



# STEP 4 — CONFIGURING NGINX TO USE PHP PROCESSOR

sudo mkdir /var/www/projectLEMP 


![sudo mkdir](Images/sudo-mkdir.jpg)



sudo chown -R $USER:$USER /var/www/projectLEMP

![sudo chown](Images/sudo-chown.jpg)


sudo nano /etc/nginx/sites-available/projectLEMP


![sudo nano](Images/sudo-nano.jpg)



 sudo ln -s /etc/nginx/sites-available/projectLEMP /etc/nginx/sites-enabled/

![ln -s](Images/sudo-ln.jpg)


sudo nginx -t

![nginx -t](Images/sudo-nginx-t.jpg)



sudo unlink /etc/nginx/sites-enabled/default

![unlink](Images/sudo-unlink.jpg)


$ sudo systemctl reload nginx

![systemctl](Images/sudo-systemctl.jpg)


LEMP Stack Page
![LEMP Stack Page](Images/lemp-stack.jpg)



# STEP 5 – TESTING PHP WITH NGINX

sudo nano /var/www/projectLEMP/info.php


![nano](Images/nano-php.jpg)

sudo rm /var/www/your_domain/info.php


# STEP 6 – RETRIEVING DATA FROM MYSQL DATABASE WITH PHP

sudo mysql -p

![mysql](Images/sudo-mysql-p.jpg)



CREATE DATABASE example_database; 

![mysql](Images/creating-database.jpg)

CREATE USER AND SHOW DATABASE

![mysql](Images/show-database.jpg)

TO DO Code

![mysql](Images/todo-code.jpg)


To Do Webpage APP


![mysql](Images/todo-webpage.jpg)
