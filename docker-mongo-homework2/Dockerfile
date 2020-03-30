FROM openjdk:8
RUN mkdir /projects
ADD target/products.jar /projects/
EXPOSE 8888
ENTRYPOINT ["java", "-Dspring.profiles.active=container", "-jar", "products.jar"]