# Docker Images for Development

This repository mainly contains the source for Docker images used in development. See the respective subdirectories for details.

## Images

### [ubuntu4dev](/ubuntu4dev)

An ubuntu image with basic dev tools pre installed. [ubuntu4dev](https://github.com/ilikepy33/quickdevimage/ubuntu4dev) 

### [alpine4dev](/alpine4dev)

An alpine image with dev tools pre installed.[alpine4devs](https://github.com/ilikepy33/quickdevimage/alpine4dev) 

### [alpine4devs2](/alpine4dev)

An alpine image with advanced dev tools pre installed.[alpine4dev2](https://github.com/ilikepy33/quickdevimage/alpine4dev)

## License

All Dockerfiles are available under the MIT license.

## Instructions
Download the desired image and run the following commands:

docker load -i alpine4dev

docker run -v /c/:/temp -it alpine:latest  //for access to dev tools

run "apk update" //updating to latest packages
