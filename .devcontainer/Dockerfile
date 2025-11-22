FROM mcr.microsoft.com/devcontainers/python:3.11

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y \
        ffmpeg \
        texlive-latex-recommended \
        texlive-latex-extra \
        texlive-fonts-recommended \
        texlive-pictures \
        texlive-pstricks \
        texlive-publishers \
        libcairo2 \
        libpango-1.0-0 \
        libpangoft2-1.0-0 \
        libgl1 \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
