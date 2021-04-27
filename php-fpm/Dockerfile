FROM php:8-fpm

RUN apt-get update && apt-get upgrade -y
RUN docker-php-ext-configure mysqli && \
    docker-php-ext-install mysqli

ADD conf/www.conf /etc/php8/fpm/pool.d/www.conf
ADD conf/30-custom.ini /usr/local/etc/php/conf.d/30-custom.ini

ENTRYPOINT php-fpm --nodaemonize
VOLUME /var/www
WORKDIR /var/www
