FROM java:latest

# Permission
RUN mkdir /var/www/
RUN chmod -R 777 /var/www/
WORKDIR /var/www
COPY ./SNAPSHOT-jar-with-dependencies.jar /var/www/SNAPSHOT-jar-with-dependencies.jar
COPY ./config.properties /var/www/config.properties

CMD ["java", "-jar", "/var/www/SNAPSHOT-jar-with-dependencies.jar"]
EXPOSE "8080"