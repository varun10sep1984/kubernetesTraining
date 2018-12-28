#this is my first docker file
FROM centos:7
MAINTAINER varun.zen@gmail.com
RUN yum -y update
RUN yum -y install httpd
ADD code /var/www/html
ENV BackEnd=testLb
EXPOSE 80
CMD ["apachectl", "-D", "FOREGROUND"]