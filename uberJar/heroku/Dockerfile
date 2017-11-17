### Dockerfile

FROM openjdk:8

COPY . /usr/src/cuba-sales

CMD java -Xmx512m -Dapp.home=/usr/src/cuba-sales/home -jar /usr/src/cuba-sales/app.jar -port $PORT
