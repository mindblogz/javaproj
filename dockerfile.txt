FROM openjdk:17-jdk-alpine
WORKDIR /Desktop/devps/devps
COPY Main.java
RUN javac Main.java
CMD["java", "Main"]
