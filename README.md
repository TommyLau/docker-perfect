# docker-perfect

docker-perfect is a Swift Perfect Server boxed in a Docker image built by [Tommy Lau](https://tommy.net.cn/).

## What is in this image?

This image is a Swift Perfect web development environment cooked based on the offical docker image `swift:3.0`

## Support

- MySQL

## Get the image

```bash
docker pull tommylau/perfect
```

## Run

Start an instance:

```bash
docker run --name perfect -v /path/to/web:/server -d tommylau/swift /server/perfect-program
```

This will start an instance, and you are ready to go.

## Compile

```bash
docker run --name perfect -v /path/to/web:/server -ti tommylau/swift bash
cd /server/
swift build
```
