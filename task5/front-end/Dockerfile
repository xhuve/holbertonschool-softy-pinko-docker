FROM nginx:latest

COPY . /var/www/html/

COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]