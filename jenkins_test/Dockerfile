from 11612150650.dkr.ecr.ap-northeast-1.amazonaws.com/jenkins_test:centos
WORKDIR /home
COPY tomcat/ /home/tomcat/
RUN yum install -y java-1.8.0-openjdk  &&    yum install -y python36  &&    pip3 install awscli
EXPOSE 8080
ENTRYPOINT ["/home/tomcat/bin/catalina.sh","run"]

