[![Docker Stars](https://img.shields.io/docker/stars/jessewei/alpine-bash.svg?style=flat-square)](https://hub.docker.com/r/jessewei/alpine-bash/)
[![Docker Pulls](https://img.shields.io/docker/pulls/jessewei/alpine-bash.svg?style=flat-square)](https://hub.docker.com/r/jessewei/alpine-bash/)


Bash Docker image
=================

This image is based on Alpine Linux image, which is only a 5MB image, and
contains [Bash](https://www.gnu.org/software/bash/) (Bourne Again SHell) with
some useful tools (e.g., complete implementations of grep, sed, head, tail, and etc).

Total size of this image is only:

[![](https://badge.imagelayers.io/jessewei/alpine-bash:latest.svg)](https://imagelayers.io/?images=jessewei/alpine-bash:latest 'Get your own badge on imagelayers.io')


Usage Example
-------------

Bash prompt wait your comand or
```bash
$ docker run --rm jessewei/alpine-bash
```

Or 

```bash
$ docker run --rm jessewei/alpine-bash bash -c 'echo "Hello World"'
```
You have run this command you will get printed 'Hello World' from Bash! 

