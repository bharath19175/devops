FROM ubuntu
RUN sudo yum update
RUN sudo yum install -y default-jdk
RUN sudo yum update
EXPOSE 8080
ADD /target/my-app-1.0-SNAPSHOT.jar/ demo.jar
CMD ["java","-jar","demo.jar"]
