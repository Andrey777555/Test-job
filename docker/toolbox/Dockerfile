FROM ubuntu:14.04
MAINTAINER Yuri Trukhin <trukhinyuri@infoboxcloud.com>
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Hi, I am in your container' \
        >/usr/share/nginx/html/index.html
EXPOSE 80 
