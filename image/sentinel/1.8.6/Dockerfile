FROM openjdk:8-jre-slim
WORKDIR /
ADD https://github.com/alibaba/Sentinel/releases/download/1.8.6/sentinel-dashboard-1.8.6.jar /app.jar
EXPOSE 8080
CMD ["java", "-Dserver.port=8080", "-Dcsp.sentinel.dashboard.server=localhost:8080", "-Dproject.name=sentinel-dashboard", "-jar", "app.jar"]