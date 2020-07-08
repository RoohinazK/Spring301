  
# Zuul
FROM openjdk:8
COPY ./target/zuul-0.0.1-SNAPSHOT.war zuul-0.0.1-SNAPSHOT.war
EXPOSE 8084
CMD ["java","-jar","-Dspring.profile.active=dev"," zuul-0.0.1-SNAPSHOT.war"]
