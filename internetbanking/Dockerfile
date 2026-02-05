FROM ubuntu
RUN apt update -y && apt install apache2 -y
WORKDIR /var/www/html/
COPY index.html .
CMD ["/usr/sbin/apachectl", "-D", "FOREGROUND" ] 