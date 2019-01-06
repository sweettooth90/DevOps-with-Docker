FROM ubuntu:16.04
WORKDIR /backend-example-docker
EXPOSE 8000
RUN apt-get update && apt-get install -y curl npm nodejs git
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN git clone https://github.com/docker-hy/backend-example-docker.git
RUN npm install
CMD npm start
