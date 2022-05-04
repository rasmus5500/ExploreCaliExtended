FROM openjdk:13
ADD /explorecali-3.0.0-SNAPSHOT.jar //
ENTRYPOINT ["java", "-Dspring.profiles.active=docker", "-jar", "explorecali-3.0.0-SNAPSHOT.jar"]
