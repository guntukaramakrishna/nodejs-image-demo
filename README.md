Minimal Node.js application for intro to Docker tutorial: https://www.digitalocean.com/community/tutorials/how-to-build-a-node-js-application-with-docker

To build the docker image

    docker build -t nodejs/demo:latest .
  
To Run the docker container

    docker run --name nodejs-image-demo -p 80:8080 -d nodejs/demo:latest

