# Dockerized Spring Boot Example on Render

Based on https://www.docker.com/blog/kickstart-your-spring-boot-application-development/

Plus a couple of config lines in `application.properties`:
```
server.address=0.0.0.0
server.port=${PORT:8080}
```