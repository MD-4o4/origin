FROM ubuntu:20.04
WORKDIR /app

# Install necessary dependencies
RUN apt-get update && apt-get install -y \
    sudo \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*

EXPOSE 8080




