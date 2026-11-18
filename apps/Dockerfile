FROM php:8.3-apache
COPY index.php /var/www/html/

RUN sed -i 's/80/8080/' /etc/apache2/ports.conf /etc/apache2/sites-available/000-default.conf
USER www-data