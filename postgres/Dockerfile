FROM postgres:12-alpine

FROM nginx
EXPOSE 3010
COPY ./default.conf /etc/nginx/conf.d/default.conf
COPY ./public-html /usr/share/nginx/html