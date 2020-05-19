# Start with base image
FROM alpine

# Download and install dependency
RUN apk add --update redis

# Configure the entrypoint where the conatiner starts
CMD ["redis-server"]