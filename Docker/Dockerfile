FROM ubuntu:latest
RUN apt-get update
RUN apt-get install apache2 links -y
COPY index.html /var/www/html/index.html
EXPOSE 80
ENTRYPOINT ["apache2ctl", "-D", "FOREGROUND"]