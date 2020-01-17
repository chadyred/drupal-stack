FROM php:7.3-fpm

RUN docker-php-ext-install pdo pdo_mysql mysqli

RUN apt-get update -y && apt-get install -y sendmail libpng-dev

RUN apt-get update && \
    apt-get install -y \
        zlib1g-dev \
        libzip-dev

RUN docker-php-ext-install mbstring

RUN docker-php-ext-install zip

RUN docker-php-ext-install gd

RUN docker-php-ext-configure opcache --enable-opcache \
    && docker-php-ext-install opcache
