# UM Unprotected Service
 
This service exposes unprotected endpoints to be used as an example to demonstrate how Gatekeeper and Keycloak can be used to protect this service and authorize users' access.

**Prerequisites:** 
* [Docker](https://docs.docker.com/get-docker/)

### Build the docker image

```shell
docker build . -t um-unprotected-service
```

### Run the service

```shell
docker run -p 7070:7070 -d um-unprotected-service
```