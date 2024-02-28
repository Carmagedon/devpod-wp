# Add PHP-FPM base image
FROM php:8.2-fpm

# Install your extensions
# To connect to MySQL, add mysqli
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Install Redis
RUN pecl install redis && docker-php-ext-enable redis

