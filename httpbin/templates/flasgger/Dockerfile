FROM ubuntu
MAINTAINER NIKHIL

RUN apt-get update

ENV TZ=Asia/Kolkata

RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt install -y tzdata

RUN apt install -y apache2

COPY index.html /var/www/html/



