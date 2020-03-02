## Docker Practice - Individual Assignment II of ECE590-Cloud-Computing

#### This repo hosts files of a Docker Image, which includes:
* **Dockerfile**: a text document that contains all the commands a user could call on the command line to assemble an image.
* **app.py**: The application itself, exercise a simple functionality, 'Hello world!' text trigger by click.
* **requirements.txt**: Dependencies.
* **Makefile**: contains a set of directives for GNU make
* **push-docker.sh**: contains the commands which push docker image to Docker Hub

#### To run the Docker image:
1. Pull the docker image: `docker pull luo9137/my-first-repo`
2. Run the image: `docker run -it luo9137/my-first-repo bash`
