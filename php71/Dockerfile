FROM bitrixdock/php71-fpm:latest

MAINTAINER darbit

ADD ./php.ini /etc/php/7.1/fpm/conf.d/90-php.ini
ADD ./php.ini /etc/php/7.1/cli/conf.d/90-php.ini

RUN usermod -u 1000 www-data

WORKDIR "/home/darbit/bitrix"

EXPOSE 9000