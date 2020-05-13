# furious-heisenberg
![Docker image](https://www.docker.com/sites/default/files/d8/2019-07/horizontal-logo-monochromatic-white.png)
Docker is an open-source tool designed to make it easier, deploy, and run applications by using containers. It is a tool that is designed to benefit both developers and system administrators.
# Docker Compose
![Docker image](https://raw.githubusercontent.com/docker/compose/master/logo.png)

Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a Compose file to configure your application's services. It is great for development, testing, and staging environments. Using compose is simply a three steps process:

1. Define your app's environment with a Dockerfile so it can be reproduced anywhere.
2. Define the services that make up your app in docker-compose.yml so they can be run together in an isolated environment.
3. Lastly, run docker-compose up and Compose will start and run your entire app.
# My Project
This project is on the implementation of docker with Web Content Management System with SQL.

I have implemented WordPress with Mariadb and Drupal with Mariadb.
# Some Essesntial Commands
```
iptables -P FORWARD ACCEPT
setenforce 0
systemctl disable firewalld
firewall-cmd --zone=public --add-masquerade --permanent
firewall-cmd --zone=public --add-port=80/tcp
firewall-cmd --zone=public --add-port=443/tcp
firewall-cmd --reload
systemctl restart docker
```
