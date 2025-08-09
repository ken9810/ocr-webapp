FROM ubuntu:latest

ENV DEBIAN_FRONTEND=noninteractive

# Install Python & venv
RUN apt-get update && \
    apt-get install -y \
    python3 python3-pip python3-venv python3-full \
    tesseract-ocr libtesseract-dev \
    && rm -rf /var/lib/apt/lists/*

# Create a non-root user (best practice for devcontainers)
RUN useradd -m vscode && \
    chown -R vscode:vscode /home/vscode

USER vscode
WORKDIR /workspace
