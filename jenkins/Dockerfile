FROM jenkins/jenkins:lts
WORKDIR /jenkins
COPY job_dsl.groovy .
COPY config.yml .
COPY plugins.txt /usr/share/jenkins/ref/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt

EXPOSE 8080 50000