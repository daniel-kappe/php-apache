FROM httpd:2.4

RUN apt-get update && apt-get upgrade -y

ADD conf-available /usr/local/apache2/conf

EXPOSE 80
VOLUME /usr/local/apache2/htdocs
WORKDIR /usr/local/apache2/htdocs
