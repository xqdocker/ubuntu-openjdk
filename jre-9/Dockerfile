FROM ubuntu:16.04
MAINTAINER Xiaoqi Cao <thomascxq@gmail.com>

#Install Open JDK 9 Jre

RUN apt-get update \
    && apt-get -y install openjdk-9-jre \
    && rm -rf /var/lib/apt/lists/*

ENV JAVA_HOME /usr/lib/jvm/java-9-openjdk-amd64
ENV PATH $JAVA_HOME/bin:$PATH
