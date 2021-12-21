# spring-boot-docker-lab
Lab for running springboot with docker from official docs. https://spring.io/guides/gs/spring-boot-docker/

# build
docker build -t rodrigoborba/springboot-docker-hello .

# run 
docker run -e "SPRING_PROFILES_ACTIVE=dev" -p 8081:8081 rodrigoborba/springboot-docker-hello
