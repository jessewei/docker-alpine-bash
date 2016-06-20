[![Docker Stars](https://img.shields.io/docker/stars/jessewei/alpine-bash.svg?style=flat-square)](https://hub.docker.com/r/jessewei/alpine-bash/)
[![Docker Pulls](https://img.shields.io/docker/pulls/jessewei/alpine-bash.svg?style=flat-square)](https://hub.docker.com/r/jessewei/alpine-bash/)


Bash Docker image
=================

This image is based on Alpine Linux image, which is only a 5MB image, and
contains [Bash](https://www.gnu.org/software/bash/) (Bourne Again SHell) with
some useful tools (e.g., complete implementations of grep, sed, head, tail, and etc).



Usage Example
-------------

Bash prompt wait your comand 
```bash
$ docker run --rm jessewei/alpine-bash
```

Or 

```bash
$ docker run --rm jessewei/alpine-bash bash -c 'echo "Hello World"'
```
You have run this command you will get printed 'Hello World' from Bash! 

