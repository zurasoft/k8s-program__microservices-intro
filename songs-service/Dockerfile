# Smaller OS footprint using JRE
FROM eclipse-temurin:17-jre
WORKDIR /app

ADD build/libs/*.jar /app/app.jar

CMD ["java", "-jar", "app.jar"]