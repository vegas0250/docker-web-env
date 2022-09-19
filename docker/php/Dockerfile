FROM php:7.4.30-fpm-alpine3.16

RUN apk --no-cache add postgresql-dev
RUN docker-php-ext-install opcache pgsql pdo pdo_pgsql