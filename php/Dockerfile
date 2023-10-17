FROM php:8.2-fpm-alpine

RUN apk add --no-cache openssl bash mysql-client nodejs npm vim
RUN docker-php-ext-install pcntl pdo pdo_mysql bcmath

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer