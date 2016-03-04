# docker-telegram
Dockerfile for a Telegram gui client
A Docker image that start a fresh telegram client.

## Building

docker build -t xcellardoor/telegram .

## Usage
To spawn a new instance of Telegram:

```
docker run -it -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=unix$DISPLAY -v /dev/snd:/dev/snd xcellardoor/telegram
```

# Stopping the container
You can either log out the container, or run ```docker stop #containername#```

Thanks to [Telegram](https://telegram.org/) for their great app !
