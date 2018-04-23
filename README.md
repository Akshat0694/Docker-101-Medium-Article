# Docker 101: Your first container

__[Link to the Medium Article](https://medium.com/p/1cfaac1a272)__


This project and the medium article linked above can be used in tandem to understand docker concepts, containers in general and get hands on expreince with the tech.

Dockerfile in this project is built on top of [Ubuntu 16.04](https://store.docker.com/images/ubuntu) image, on which [supervisor](http://supervisord.org/) is installed and an entrypoint to start a process managed and controlled by supervisor utility.

## Docker CLI hints:
- Build an image
    ```
    docker build -t my_container:1.0
    # -t for tagging the images
    ```