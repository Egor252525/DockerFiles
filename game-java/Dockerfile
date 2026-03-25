FROM eclipse-temurin:17-jdk-alpine

LABEL version="1.0"

WORKDIR /app

COPY game.java .

RUN javac game.java

CMD ["java", "game"]