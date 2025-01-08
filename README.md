## An arm64 docker image for the [4get](https://git.lolcat.ca/lolcat/4get) search engine made by drifty

4get is a proxy search engine that doesn't suck.

The official images for arm64 do not exist and require building everytime, and I needed one for my Pi, so I cloned the repo and built the image myself. Useful for anyone with an arm64 processor who wants to run the engine. (Official docker repo at [```luuul/4get```](https://hubgw.docker.com/r/luuul/4get/tags))

Also available on Docker Hub - [```driftywinds/4get:latest```](https://hub.docker.com/repository/docker/driftywinds/4get/general)

How to use: - 

1. Use the docker or docker compose template from the official repo.
3. Change the "image" part of the docker-compose.yml to ```ghcr.io/driftywinds/4get:latest```.

<br>

You can check logs live with this command: - 
```
docker logs -f <container name>
```
