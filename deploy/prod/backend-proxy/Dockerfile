FROM nginx:alpine

COPY ./deploy/prod/backend-proxy/nginx.conf /etc/nginx/conf.d/default.conf

WORKDIR /var/www

COPY ./backend /var/www