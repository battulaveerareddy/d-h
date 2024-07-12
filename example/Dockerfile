FROM ubuntu

RUN apt-get update && \
    apt-get install -y apache2 &&\
    apt-get clean
     
COPY  /var/www/HTML/index.html

EXPOSE 80

CMD ["apachectl", "-D", "FOREGROUND"]