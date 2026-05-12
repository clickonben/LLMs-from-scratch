FROM nvidia/cuda:13.1.2-cudnn-devel-ubuntu24.04

RUN apt-get update && apt-get install -y \
    python3 python3-pip python3-venv git build-essential \
    && rm -rf /var/lib/apt/lists/*

RUN pip3 install --upgrade pip