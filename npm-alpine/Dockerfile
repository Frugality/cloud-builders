# Use the base App Engine Docker image, based on debian jessie.
FROM node:7.10-alpine

# Install updates and dependencies
RUN apk add --no-cache make gcc g++ python openssh-client

ENTRYPOINT ["npm"]
