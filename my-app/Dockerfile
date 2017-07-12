FROM ubuntu
RUN yum update
RUN yum install -y default-jdk
RUN yum update
EXPOSE 8080
ADD /target/my-app-1.0-SNAPSHOT.jar/ demo.jar
CMD ["java","-jar","demo.jar"]
