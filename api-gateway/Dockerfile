FROM openjdk:17
LABEL authors="cuongbuilh@gmail.com"

EXPOSE 8080

COPY target/*.jar /app.jar

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

CMD ["/entrypoint.sh"]