## Getting started:
Load the develop environment
```bash
$ mkdir myApp
$ cd myApp
$ git clone https://github.com/McMenemy/GoDoRP.git .
$ docker-compose up
```

Changing any frontend (React) code locally will cause a hot-reload in the browser with updates and changing any backend code locally will also automatically update any changes.

Then to build production images run:
```bash
$ docker build ./frontend --build-arg app_env=production
```
