FROM php:7.0-fpm
RUN apt-get update && apt-get install -y libmcrypt-dev zlib1g-dev \
    && docker-php-ext-install \
        pdo_mysql \
        mcrypt \
        mbstring \
        tokenizer \
        zip