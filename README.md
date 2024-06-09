# spring-boot-docker
This is a simple application to teach how to start developments with docker. This is the blog post how to Dockerize Spring Boot Application and run and use it. 
( https://bawadev.github.io/post/dev-docker/ )

# Build Docker Image 
$ docker build -t spring-boot-docker.jar .

# Check Docker Image 
$ docker image ls

# Run Docker Image 
$ docker run -p 9090:8080 spring-boot-docker.jar

In the run command, we have specified that the port 8080 on the container should be mapped to the port 9090 on the Host OS.
