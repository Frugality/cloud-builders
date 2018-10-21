FROM gcr.io/intense-signer-183616/npm-ssh

# Install the latest stable release of Yarn
RUN mkdir /yarn && curl -L https://github.com/yarnpkg/yarn/releases/download/v0.24.6/yarn-v0.24.6.tar.gz | tar xvzf - -C /yarn --strip-components=1
ENV PATH $PATH:/yarn/bin

ENTRYPOINT ["yarn"]
