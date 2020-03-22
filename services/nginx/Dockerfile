FROM    nginx:stable-alpine

LABEL   maintainer="Dante Lopez <dante@dqlopez.com>"

WORKDIR /var/www/html

RUN     rm /etc/nginx/conf.d/default.conf

COPY    nginx.conf /etc/nginx/

COPY    default.conf /etc/nginx/conf.d/

EXPOSE  80