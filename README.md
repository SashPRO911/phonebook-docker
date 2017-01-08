# Phonebook docker images
==============================

Before use, download Docker http://www.docker.io

### First image - run phonebook.jar app

To build the first image with docker:

    cd first
    docker build -t first .

Then to run that image :

    docker run first

### Second image - build Phonebook and create ".jar" app, ".jar" would be in directory where you run docker

To build the secong image with docker:

    cd second
    docker build -t second .

Then to run that image :

    docker run -v $(pwd):/target second
