FROM php:7-fpm-alpine

RUN apk add --no-cache \
        $PHPIZE_DEPS \
        openssl-dev \
        composer

RUN pecl install xdebug

WORKDIR /app
