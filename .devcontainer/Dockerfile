FROM mcr.microsoft.com/devcontainers/base:1.0.0-alpine-3.19

USER vscode

RUN apt-get update && apt-get install -y watchman \ && npm install -g eas-cli expo-cli

EXPOSE 8081 19000 19001 19002