FROM centos:latest
MAINTAINER yulaufe
RUN yum -y install java-1.8.0-openjdk-devel.x86_64
ENV NAME yuv
RUN mkdir /logs
RUN yum -y install tomcat
CMD tomcat start && tail -f /logs/catalina.out
