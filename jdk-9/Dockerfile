FROM ubuntu:16.04
MAINTAINER Xiaoqi Cao <thomascxq@gmail.com>

#Install Open JDK 9

RUN apt-get update \
    && apt-get -o Dpkg::Options::="--force-overwrite" install openjdk-9-jdk \
    && rm -rf /var/lib/apt/lists/*

ENV JAVA_HOME /usr/lib/jvm/java-9-openjdk-amd64
ENV PATH $JAVA_HOME/bin:$PATH
