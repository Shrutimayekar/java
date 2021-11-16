FROM openjdk:8
ARG JAR_FILE=target/hello_boot.jar
COPY ${JAR_FILE} hello_boot.jar
EXPOSE 8780
ENTRYPOINT ["java","-jar","/hello_boot.jar"]