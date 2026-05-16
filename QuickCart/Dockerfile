# Use PHP with Apache
FROM php:8.2-apache

# Install mysqli extension (needed for most PHP/MySQL projects)
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

# Copy the contents of your QuickCart folder to the web server
COPY ./QuickCart/ /var/www/html/

# Expose the port
EXPOSE 80
