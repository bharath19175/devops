FROM centos:7
RUN yum update
EXPOSE 8080
ADD /target/my-app-1.0-SNAPSHOT.jar/ demo.jar
CMD ["java","-jar","demo.jar"]
