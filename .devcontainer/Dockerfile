FROM mcr.microsoft.com/devcontainers/cpp:1-ubuntu-22.04

# Install additional C++ development tools
RUN apt-get update && apt-get install -y \
    build-essential \
    cmake \
    gdb \
    valgrind \
    clang \
    clang-format \
    && rm -rf /var/lib/apt/lists/*
