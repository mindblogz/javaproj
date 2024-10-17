FROM openjdk:17-jdk-allpine
WORKDIR /Desktop/devps/devps
COPY Main.java
RUN javac Main.java
CMD["java", "Main"]
