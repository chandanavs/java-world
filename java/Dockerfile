FROM openjdk:8

WORKDIR /java

COPY HelloWorld.java /java

RUN javac HelloWorld.java

ENTRYPOINT [ "java", "HelloWorld" ]