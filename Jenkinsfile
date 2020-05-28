FROM jenkins
MAINTAINER sunil
VOLUME /data
ADD http://mirrors.jenkins.io/war-stable/latest/jenkins.war /
USER root
RUN apt-get update
RUN apt-get install -y openjdk-8-jdk
ENTRYPOINT ["java","-jar","jenkins.war"]
EXPOSE 8080

