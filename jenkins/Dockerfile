FROM jenkins:2.19.1

USER root
RUN apt-get update \
    && apt-get install -y apt-utils \
    && apt-get install -y docker.io \
    && usermod -G docker jenkins

USER jenkins
