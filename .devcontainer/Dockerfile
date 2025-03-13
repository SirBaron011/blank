# Use the latest Ubuntu image as the base
FROM ubuntu:latest

# Update package lists and install some basic tools
RUN apt-get update && apt-get install -y \
    build-essential \
    curl \
    wget \
    git \
 && rm -rf /var/lib/apt/lists/*

# Set the default shell to bash
CMD ["/bin/bash"]
