FROM ubuntu:18.04
RUN apt-get update && \
        apt-get -y upgrade && \
        apt-get -qq -y --fix-missing install apt-utils \
        php7.2-opcache \        
        php7.2-cli \
        apt-get install httpd \
        php7.2-common 

COPY index.php /var/www/html

EXPOSE 80

FROM PHP 

