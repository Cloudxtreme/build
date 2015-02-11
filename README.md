Docker Build
============

Official builds are produced using a Docker image specified by the
Dockerfile in this directory. The following command, executed in the
syncthing source directory, exactly reproduce the official build
process.

```
./build.sh docker-all
```

> This uses a temporary container with the image from above and a volume
> mapped to the directory containing the source. Tests are run and
> binary packages created.
