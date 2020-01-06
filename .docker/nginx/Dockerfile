FROM php:7.4.1-fpm-alpine3.11

WORKDIR /var/www
RUN rm -rf /var/www/html

COPY . /var/www
RUN ln -s public html

EXPOSE 9000

ENTRYPOINT ["php-fpm"]
