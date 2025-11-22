FROM mcr.microsoft.com/devcontainers/python:3.11

# 1) 시스템 패키지 (ffmpeg + LaTeX + manim이 쓰는 라이브러리)
RUN apt-get update && apt-get install -y \
    ffmpeg \
    texlive-full \
    libcairo2 \
    libpango-1.0-0 \
    libpangoft2-1.0-0 \
    libgl1-mesa-glx \
    && apt-get clean && rm -rf /var/lib/apt/lists/*

# (선택) locale 설정이 필요하면 여기 추가 가능
