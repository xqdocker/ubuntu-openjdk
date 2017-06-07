FROM ubuntu:14.04
MAINTAINER Xiaoqi Cao <thomascxq@gmail.com>

#Install Open JDK 6 Jre

RUN apt-get update \
    && apt-get -y install openjdk-6-jre \
    && rm -rf /var/lib/apt/lists/*

ENV JAVA_HOME /usr/lib/jvm/java-6-openjdk-amd64
ENV PATH $JAVA_HOME/bin:$PATH
