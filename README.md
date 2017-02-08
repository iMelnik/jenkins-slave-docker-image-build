# Jenkins Slave for docker-in-docker builds

This Dockerfile produces a jenkins slave image, that contains the necessary rights to build docker images inside a build pod. Be sure to map the following host paths into the container:

* /run/docker.sock
* /var/run/docker.sock

The image is available at https://hub.docker.com/r/nbyl/jenkins-slave-docker-image-build/
