# Use existing docker image
FROM alpine

# Download and install a dependencies

RUN apk add --update redis
RUN apk add --update gcc

# Command after starting up the image

CMD ["redis-server"]
