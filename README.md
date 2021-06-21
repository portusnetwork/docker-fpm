# docker-fpm

Use it from the [Docker Hub](http://hub.docker.com/r/portusnetwork/fpm).

## Deb packages

Uses Ubuntu Xenial

```
docker build -t portusnetwork/fpm:ubuntu18.04 deb
docker push portusnetwork/fpm:ubuntu18.04
```

## RPM packages

Uses CentOS 7

```
docker build -t portusnetwork/fpm:centos-7 rpm
docker push portusnetwork/fpm:centos-7
```

## Custom Linux distributions

For another deb-flavored distro, change the `FROM` in the `deb/Dockerfile`.

For another rpm-flavored distro, change the `FROM` in the `rpm/Dockerfile`.
