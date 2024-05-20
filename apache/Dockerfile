FROM debian:latest
RUN apt update && apt install -y apache2
RUN a2enmod ssl rewrite
ENTRYPOINT [ "apachectl" , "-D" , "FOREGROUND" ]