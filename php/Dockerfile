# Add PHP-FPM base image
FROM php:8.2-fpm

# Install your extensions
# To connect to MySQL, add mysqli
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Copy composer.lock and composer.json
COPY composer.lock composer.json /var/www/
