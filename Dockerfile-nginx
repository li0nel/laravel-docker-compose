FROM nginx

ADD deploy/nginx/nginx.conf /etc/nginx/
ADD deploy/nginx/default.conf /etc/nginx/conf.d/

ADD public /usr/share/nginx/html

WORKDIR /usr/share/nginx/html