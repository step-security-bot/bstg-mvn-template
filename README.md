## Developer Playbook

```sh
mvn clean package
# Build Image with Dockerfile
docker build -t <tag> .
# Build Image with Spring Boot
mvn spring-boot:build-image
```
