FROM nginx:stable-alpine

COPY ./docker/nginx/default.conf /etc/nginx/conf.d/default.conf

RUN mkdir -p /app/public
COPY ./public /app/public