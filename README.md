# empi89/shairport
Shairport container from jbor/shairport customized to run on a Raspberry PI 2. See original repo for more information. You may use hypriot (http://blog.hypriot.com) to run Docker on RPi.

### Requirements
* armelbuild/debian:jessie
* Alsa sound enabled on host

### Build
```sh
docker build -t empi89/shairport .
```

### Run
```sh
./run-with-docker
```

### Credits
* This is forked from  jbor/shairport
* Inspired by the RPi Dockerfile from djmaze

### Docker Repository
https://registry.hub.docker.com/u/empi89/shairport/
