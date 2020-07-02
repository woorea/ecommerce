FROM openjdk:14-alpine
COPY target/ecommerce-monolith-*.jar ecommerce-monolith.jar
EXPOSE 8080
CMD ["java", "-Dcom.sun.management.jmxremote", "-Xmx128m", "-jar", "ecommerce-monolith.jar"]