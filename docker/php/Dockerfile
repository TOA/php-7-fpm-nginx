FROM php:7-fpm

RUN docker-php-ext-install pdo \
    && docker-php-ext-install pdo_mysql \
    && docker-php-ext-install mysqli

CMD ["php-fpm"]