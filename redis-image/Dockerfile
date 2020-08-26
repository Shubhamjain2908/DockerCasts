# Use an existing docker image as a base
FROM alpine

# Dowwnload & install a dependency
RUN apk add --update redis

# Tell the image what to do when it starts as container
CMD [ "redis-server" ]