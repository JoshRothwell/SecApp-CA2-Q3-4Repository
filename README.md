My Project

> This repository is for the **main** branch.

docker network create my-network

docker run -d --name db -e MYSQL_ROOT_PASSWORD=my-secret-password mysql:latest


docker run -d --name phpmyadmin -p 8080:80 --network=my-network -e PMA_HOST=db phpmyadmin/phpmyadmin
