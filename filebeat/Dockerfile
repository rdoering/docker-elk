FROM ubuntu:14.04

RUN apt-get update && apt-get install -y wget apt-transport-https
RUN wget -qO -  https://packages.elastic.co/GPG-KEY-elasticsearch | sudo apt-key add -
RUN echo 'deb https://packages.elastic.co/beats/apt stable main' > /etc/apt/sources.list.d/beats.list
RUN apt-get update && apt-get install filebeat
