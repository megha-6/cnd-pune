FROM php:7.4-apache
COPY ./index.php /var/www/html/
EXPOSE 80
WORKDIR /var/www/html
CMD ["php", "-S", "0.0.0.0:80", "-t", "/var/www/html/"]

