FROM openjdk:10.0.2-jre-slim
COPY target/microservice-consuldns-demo-order-0.0.1-SNAPSHOT.jar .
CMD /usr/bin/java -Dlogging.path=/log/ -Xmx400m -Xms400m -jar microservice-consuldns-demo-order-0.0.1-SNAPSHOT.jar
EXPOSE 8080
