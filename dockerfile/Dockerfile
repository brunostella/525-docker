FROM ubuntu
RUN apt update
RUN apt install wget git figlet apache2 -y
RUN apt clean
COPY hosts /tmp/
COPY index.html /var/www/html/
CMD httpd -D foreground
