FROM node:8.1-alpine

# Install updates and dependencies
RUN apk add --no-cache make gcc g++ python openssh-client curl git

# Install the latest stable release of Yarn
RUN mkdir /yarn && curl -L https://github.com/yarnpkg/yarn/releases/download/v0.24.6/yarn-v0.24.6.tar.gz | tar xvzf - -C /yarn --strip-components=1
ENV PATH $PATH:/yarn/bin

ENTRYPOINT ["yarn"]
