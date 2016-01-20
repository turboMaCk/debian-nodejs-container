# Debian & Node.js Docker container
Docker container to run Node.js apps on top of Deabian. Design mostly in Koa.js in mind

## Get image

There is an [Automated Build on hub.docker.com](https://hub.docker.com/r/turbomack/debian-nodejs-container/), so getting the image is easy:

```bash
$ docker pull turbomack/debian-nodejs-container:latest
```

## Run image

Run it from inside a Docker container:

```bash
$ docker run -it --rm turbomack/debian-nodejs-container
```

## Build image from repository

You can build this image on your own.

```bash
$ git clone git@github.com:turboMaCk/debian-nodejs-container.git
$ cd ember-test-container
$ docker build -t turbomack/debian-nodejs-container:latest .
```

## License
MIT (c) Marek Fajkus 2016
