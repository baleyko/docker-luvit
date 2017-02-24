# Luvit Docker Image Source

[![Build Status](https://travis-ci.org/baleyko/docker-luvit.png?branch=master)](https://travis-ci.org/baleyko/docker-luvit)

It's a source code of docker image with [Luvit](https://luvit.io/).
Luvit - it's a lightweight implementation of Lua programming language, using the event loop, distribute with a standard library that implements similiar to the Node.js standard library interface.
Read the official documentation to learn more.

Right now, you can build it from these sources:

```shell
$ git clone https://github.com/baleyko/docker-luvit.git
$ docker build -t luvit .
$ docker run --rm -it luvit -e 'print("Hello World!")'
```

Either use the docker image from the hub(current Luvit version: 3.5.2):

```shell
$ docker run --rm -it luvit:latest -e 'print("Hello World!")'
```

## License
  
It's distributed under [MIT License](LICENSE).
