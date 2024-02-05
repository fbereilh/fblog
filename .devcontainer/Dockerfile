# Use the official Python image
FROM python:3.9

# Install dependencies for Quarto and JupyterLab
RUN apt-get update && apt-get install -y wget pandoc gdebi

# Install Quarto
RUN curl -LO https://quarto.org/download/latest/quarto-linux-amd64.deb
RUN gdebi --non-interactive quarto-linux-amd64.deb

WORKDIR /home


