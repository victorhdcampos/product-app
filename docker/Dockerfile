FROM ubuntu:23.10
WORKDIR /app
ENV DB_USER=postgres
ENV DB_PASSWORD=123456
RUN apt-get update
RUN apt-get install -y default-jre
COPY product-0.0.1-SNAPSHOT.jar product.jar
EXPOSE 8083
ENTRYPOINT ["java", "-jar","product.jar"]