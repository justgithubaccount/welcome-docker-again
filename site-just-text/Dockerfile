FROM debian:latest

RUN apt update -y
RUN apt install nginx -y

RUN echo '<center><b>Nginx is Up</b></center>' \
    > /var/www/html/index.html

CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80