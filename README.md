# dockerfile-example

Create Docker Image
--------------------
docker build -t cents-os-tomcat9 -f TomcatDockerfile .


Start Docker Container
--------------------
docker run -d -p 8080:8080 cents-os-tomcat9

docker run -it --rm -p 8080:8080 cents-os-tomcat9



Start Docker Container with Interactive mode
--------------------
docker run -it cents-os-tomcat9 /bin/bash