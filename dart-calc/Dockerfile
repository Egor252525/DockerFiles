FROM dart:stable

LABEL version="1.0"

WORKDIR /app

COPY calc.dart .

RUN dart compile exe calc.dart -o calc

CMD ["./calc"]