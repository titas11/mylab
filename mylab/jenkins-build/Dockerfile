FROM jenkins/jenkins:alpine-jdk11

COPY plugins.txt /var/jenkins_home/plugins.txt
RUN  jenkins-plugin-cli -f /var/jenkins_home/plugins.txt
