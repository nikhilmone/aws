```
sudo yum install epel-release
sudo yum install docker
sudo yum-config-manager --enable epel
sudo yum install ansible
sudo yum install java-1.8.0-openjdk-devel
sudo wget http://repos.fedorapeople.org/repos/dchen/apache-maven/epel-apache-maven.repo -O /etc/yum.repos.d/epel-apache-maven.repo
sudo sed -i s/\$releasever/6/g /etc/yum.repos.d/epel-apache-maven.repo
sudo yum install -y apache-maven
mvn --version
sudo update-alternatives --config java
sudo update-alternatives --config javac
```

```
ssh -i "aws-mac.pem" ec2-user@ec2-18-216-165-133.us-east-2.compute.amazonaws.com
```
## Install NGINX
$ sudo yum install nginx -y

## Install PHP and PHP-FPM
$ sudo yum install php -y
$ sudo yum install php-fpm -y

## Configure NGINX (see below)
$ sudo nano /etc/nginx/conf.d/default.conf

## Configure PHP-FPM (see below)
$ sudo nano /etc/php-fpm.d/www.conf

## Add NGINX and PHP-FPM service start to boot sequence
$ sudo chkconfig nginx on
$ sudo chkconfig php-fpm on

## Start NGINX and PHP-FPM service
$ sudo service nginx start
$ sudo service php-fpm start

## Add <file>.php to /var/www/html
## Verify configuration via http://www.domain.com/<file>.php
  
   65  service nginx status
   66  sudo mkdir /etc/ssl/private
   67  sudo chmod 700 /etc/ssl/private
   68  sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/ssl/private/nginx-selfsigned.key -out /etc/ssl/certs/nginx-selfsigned.crt
   69  sudo ls -al /etc/ssl/private/
   70  sudo su
   71  sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/ssl/private/nginx-selfsigned.key -out /etc/ssl/certs/nginx-selfsigned.crt
   72  sudo openssl dhparam -out /etc/ssl/certs/dhparam.pem 2048
   73  sudo vi /etc/nginx/conf.d/ssl.conf
   
   
