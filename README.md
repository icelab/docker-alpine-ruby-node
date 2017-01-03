# Alpine Linux Docker image for Ruby & Node

## Building and publishing the image

Build the image:

```
docker build -t alpine-ruby-node .
```

Get the image ID:

```
docker images
```

Tag the image:

```
docker tag <image_id> icelab/alpine-ruby-node:latest
```

Log into the Docker hub:

```
docker login
```

Push the image:

```
docker push icelab/alpine-ruby-node
```
