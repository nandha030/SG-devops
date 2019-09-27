#Base Image
FROM ubuntu:16.04

#onwer
MAINTAINER nandha030<nandhavignesh2010@gmail.com>

#Update Ubuntu
RUN apt-get update

# install apache2
RUN  apt-get install apache2 -y

# Copy the Code. 
COPY info.html /var/www/html/

# connect the port 
EXPOSE 80 8080

# Excute the Service 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

