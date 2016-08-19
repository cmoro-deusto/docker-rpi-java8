# docker-rpi-java8

[![dockeri.co](http://dockeri.co/image/dordoka/rpi-java8)](https://registry.hub.docker.com/u/dordoka/rpi-java8/)

Raspberry Pi compatible Docker base image with Java.

Uses ARM `oracle-java8-installer` from webupd8team. See [this](http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html).

Run all the commands from within the project root directory.

### Build Details
- [Source Repository](https://github.com/cmoro-deusto/docker-rpi-java8)
- [Dockerfile](https://github.com/cmoro-deusto/docker-rpi-java8/blob/master/Dockerfile)
- [DockerHub] (https://registry.hub.docker.com/u/dordoka/rpi-java8/)


#### Build the Docker Image
```bash
make build
```

#### Run the Docker Image and get the version of installed Java Runtime Environment
```bash
make version
```

#### Push the Docker Image to the Docker Hub
* First use a `docker login` with username, password and email address
* Second push the Docker Image to the official Docker Hub

```bash
make push
```

Kudos to [Hypriot](http://blog.hypriot.com/heavily-armed-after-major-upgrade-raspberry-pi-with-docker-1-dot-5-0)

## License

The MIT License (MIT)

Copyright (c) 2015 Carlos Moro

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
