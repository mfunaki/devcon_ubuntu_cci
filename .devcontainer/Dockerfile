FROM mcr.microsoft.com/devcontainers/base:jammy

# Allow GPG signing from inside of a container
RUN apt-get update && apt-get install gnupg2 -y

# Install CircleCI CLI
RUN curl -fLSs https://raw.githubusercontent.com/CircleCI-Public/circleci-cli/master/install.sh | bash
