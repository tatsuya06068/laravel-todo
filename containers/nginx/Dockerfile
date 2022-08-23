FROM nginx:1.22-alpine

ENV TZ Asia/Tokyo

# nginx config file
COPY ./containers/nginx/*.conf /etc/nginx/conf.d/

WORKDIR /var/www