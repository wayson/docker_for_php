FROM php:7.0-fpm
RUN apt-get update && apt-get install -y libmcrypt-dev zlib1g-dev \
    && apt-get install -y libmagickwand-dev --no-install-recommends \
    && pecl install imagick \
    && docker-php-ext-enable imagick \
    && docker-php-ext-install \
        pdo_mysql \
        mcrypt \
        mbstring \
        tokenizer \
        zip \
        xml \
        gd \
        bcmath