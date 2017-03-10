# docker-android

This is a base image, used for our GitLab CI as a shared runner. Packages
are included to build our Android libraries and apps.


## Build local image

```bash
$ docker build -t android:25.0.2 .
```

This takes a while, since all packages from the Dockerfile need to be installed.

## Start local instance of the container

Connect to local container with a bash:

```bash
$ docker run --rm -it android:25.0.2 bash
```
