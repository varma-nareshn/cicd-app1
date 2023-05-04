FROM openjdk:8
COPY  /home/jenkins/agent/workspace/docker-maven-demo/cicd-app1/target/my-app-1.0-SNAPSHOT.jar  myapp.jar

ENTRYPOINT  [ "java" , "-jar" ,  "myapp.jar"  ]

