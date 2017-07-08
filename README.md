# Docker Web Environment

### Description
This is a simple environment on the Docker for your web application. This image provides Nginx and PHP-FPM with minimal settings. You can use it as a base image with further customization. Or just take it and run your application.

### Usage example
```
git clone git@github.com:Subb98/Docker-Web-Environment.git
cd Docker-Web-Environment
docker-compose build
docker-compose up -d
curl -I http://localhost:80
```
