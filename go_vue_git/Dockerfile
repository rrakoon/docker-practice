# ubuntu-openjdk-8-jdk
#
# VERSION               0.0.3
#
# Extends ubuntu-base with java 8 openjdk jdk installation
#
FROM ubuntu:bionic

# This is in accordance to : https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-get-on-ubuntu-16-04
RUN apt-get update && \
	apt-get -y upgrade && \
	apt install -y curl && \
	apt install -y wget;
	
# golang install
RUN apt-get install -y golang-go;


# nodejs install
RUN curl -sL https://deb.nodesource.com/setup_14.x -o nodesource_setup.sh && \
	bash nodesource_setup.sh;

RUN	apt-get update && \
	apt-get -y upgrade && \
	apt-get -y install nodejs && \
	apt-get -y install build-essential;


# git install
RUN apt update && \
	apt install -y git;