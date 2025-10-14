FROM mcr.microsoft.com/devcontainers/base:ubuntu

RUN apt-get update && apt-get install -y wget gdebi-core \
 && wget -q https://quarto.org/download/latest/quarto-linux-amd64.deb \
 && gdebi -n quarto-linux-amd64.deb \
 && rm quarto-linux-amd64.deb