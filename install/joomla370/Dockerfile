# Dockerfile
# syntax=docker/dockerfile:1

# Dockerfile
FROM php:7.0-apache



RUN apt-get update && apt-get install -y \
    zlib1g-dev \
    libzip-dev \
    libpng-dev \
    libicu-dev


RUN docker-php-ext-configure zip && docker-php-ext-install mysqli zip gd intl && docker-php-ext-enable mysqli zip gd intl

COPY ./app /var/www/html




