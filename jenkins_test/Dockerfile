from centos:8
WORKDIR /home
COPY tomcat/ /home/tomcat/
RUN yum install -y java-1.8.0-openjdk  &&    yum install -y python36  &&    pip3 install awscli
EXPOSE 8080
ENTRYPOINT ["/home/tomcat/bin/catalina.sh","run"]

