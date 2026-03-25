FROM eclipse-temurin:17-jdk-alpine

LABEL version="1.0"

WORKDIR /app

COPY calc.java .

RUN javac calc.java

CMD ["java", "calc"]