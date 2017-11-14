FROM php:7.0-fpm
RUN apt-get update && apt-get install -y git 
COPY .env* /var/www/html/
VOLUME ["/var/www/html/"]