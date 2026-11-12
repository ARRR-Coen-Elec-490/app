FROM mcr.microsoft.com/devcontainers/base:alpine

USER vscode

RUN apt-get update && apt-get install -y watchman \ && npm install -g eas-cli expo-cli

EXPOSE 8081 19000 19001 19002