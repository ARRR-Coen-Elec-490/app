FROM mcr.microsoft.com/devcontainers/typescript-node:1-22-bookworm

USER root

RUN apt-get update \
    && apt-get install -y --no-install-recommends watchman \
    && rm -rf /var/lib/apt/lists/*

USER node

EXPOSE 8081 19000 19001 19002
