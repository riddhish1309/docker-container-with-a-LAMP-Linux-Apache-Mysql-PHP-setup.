FROM php:7.2-apache
RUN apt-get update
RUN apt-cache search mysql-server
COPY src/ /var/www/html/
EXPOSE 80
