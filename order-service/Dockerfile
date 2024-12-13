FROM openjdk:21

WORKDIR /usr/application/

COPY target/order-service-0.0.1-SNAPSHOT.jar order.jar

EXPOSE 8084

CMD ["java", "-jar", "order.jar"]