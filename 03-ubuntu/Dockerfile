FROM ubuntu:latest

RUN apt-get update && \
	apt-get install -y openjdk-17-jdk && \
	apt-get install -y ant && \
	apt-get clean;

ENV JAVA_HOME /usr/lib/jvm/java-17-openjdk-amd64/

RUN export JAVA_HOME