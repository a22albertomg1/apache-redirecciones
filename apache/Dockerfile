FROM debian:latest
RUN apt update && apt install -y apache2
RUN a2enmod ssl
ENTRYPOINT [ "apachectl" , "-D" , "FOREGROUND" ]