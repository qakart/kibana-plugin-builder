kibana-plugin-builder
=====================

[![Circle CI](https://circleci.com/gh/blacktop/kibana-plugin-builder.png?style=shield)](https://circleci.com/gh/blacktop/kibana-plugin-builder) [![License](http://img.shields.io/:license-mit-blue.svg)](http://doge.mit-license.org) [![Docker Stars](https://img.shields.io/docker/stars/blacktop/kibana-plugin-builder.svg)](https://store.docker.com/community/images/blacktop/kibana-plugin-builder) [![Docker Pulls](https://img.shields.io/docker/pulls/blacktop/kibana-plugin-builder.svg)](https://store.docker.com/community/images/blacktop/kibana-plugin-builder) [![Docker Image](https://img.shields.io/badge/docker%20image-1.07GB-blue.svg)](https://store.docker.com/community/images/blacktop/kibana-plugin-builder)

> Kibana Plugin Builder

---

### Dependencies

-	[alpine:3.6](https://hub.docker.com/_/alpine/)

### Image Tags

```bash
REPOSITORY          TAG                 SIZE
blacktop/kibana-plugin-builder     latest              1.07GB
blacktop/kibana-plugin-builder     5.5.0               1.07GB
blacktop/kibana-plugin-builder     node                54.2MB
```

> **NOTE:** tag `node` is the base image that has the appropriate version of NodeJS for the version of Kibana you are using to build your plugin (it default to the version needed for latest)

Build
-----

```
$ git clone https://github.com/blacktop/kibana-plugin-builder.git
$ cd kibana-plugin-builder
$ make build
```
