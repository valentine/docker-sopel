# Sopel Docker Image

A Docker image for [Sopel](https://github.com/sopel-irc/sopel).

> Sopel is a simple, lightweight, open source, easy-to-use IRC Utility bot, written in Python. It's designed to be easy to use, run and extend.

## Installation

Pull [the image](https://hub.docker.com/r/valentine/sopel/) from Docker Hub:

    docker pull valentine/sopel:latest

Create a container using `docker run`:
    
    docker run -d \
      -v /path/to/sopel:/sopel \
      valentine/sopel:latest
    
The above, in one line:

    docker run -d -v /path/to/sopel:/sopel valentine/sopel:latest

## Licence

Code licensed under The MIT License (MIT).