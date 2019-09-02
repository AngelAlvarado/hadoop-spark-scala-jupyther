FROM openjdk:8-alpine

MAINTAINER Angel Alvarado <angel.angelio@gmail.com>

RUN apk --update add wget tar bash

RUN wget http://ftp.wayne.edu/apache/spark/spark-2.4.4/spark-2.4.4-bin-hadoop2.7.tgz

RUN tar -xzf spark-2.4.4-bin-hadoop2.7.tgz 
RUN mv /spark-2.4.4-bin-hadoop2.7 /spark