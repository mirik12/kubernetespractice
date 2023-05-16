FROM php:7.4-apache

RUN apt-get update && apt-get install -y \
    curl \
    libpng-dev \
    libonig-dev \
    libxml2-dev \
    zip \
    unzip \
    && docker-php-ext-install pdo_mysql mysqli gd opcache

COPY ./index.php /var/www/html/index.php

CMD ["apache2-foreground"]

EXPOSE 80