# Docker
//all what you need for docker

//--install mysql image
$docker pull mysql

//--install phpmyadmin
$docker pull phpmyadmin

//--create docker-compose.yml file on your project
$cd project-name 
$:> docker-compose.yml

//--create .env file on your project
/project-name:$:> .env

//to start work on mysql
$docker exec -it mysql mysql -uroot -p
Enter password: root
mysql>

//now entry to see your database with phpmyadmin
$sudo docker-compose up -d

//in your web browser 
http://localhost:8080

//install php with apache
$docker pull php:7.2.3-apache-stretch


