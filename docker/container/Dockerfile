FROM php:7.4.8-apache

#Install composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

#Apache vhost conf
COPY 000-default.conf /etc/apache2/sites-available/000-default.conf