"# docker-practice" 


## Containers
- Allow running multiple apps in isolation
- Are lightweight
- Use OS of the host
- Start quickly
- Need less hardware resources

## Docker
Docker use a client-server architecture. It utilize a container to independently run an application regardless of the OS.

check docker version
```
docker version
```

run applicaction through docker
```
docker run ...
```

build docker image
```
docker build -t <filename> <directory>

docker build -t <name>/<reponame>:<tag> .
```

tag docker image
```
docker tag <imageID> <reponame>/<imagename>:tag
```

view docker images
```
docker image ls
```
