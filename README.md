# hunt
All the things needed to get up and running with a basic bug hunting repo in a docker container.

## Installation
Run `install` to get the environment setup with docker-ce. Note: this script was created to run on Ubuntu 19.10

## Building the Docker Image
Run `build` to create the docker image from the ubuntu base image and the additional commands included inside the Dockerfile. Currently the image is built with git being installed and then the `bbht` repo being cloned into the home folder of the docker container.

## Starting the Docker Container
Run `start` to start up the docker container interactively. Then, navigate to the ~/bbht directory and run the install.sh script that was originally created by @NahamSec, and modified based on the differences of being in a docker container.
