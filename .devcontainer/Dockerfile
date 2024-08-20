FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package
RUN apt-get update && \
    apt-get install -y python3-pip && \
    pip install --no-cache-dir django mongodb
