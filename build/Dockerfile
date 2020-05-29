FROM ubuntu:latest
RUN apt-get -qq update && \
    apt-get install -y apache2 && \
    apt-get clean
COPY goda/index.html /var/www/html/
EXPOSE 80
CMD apachectl -D FOREGROUND