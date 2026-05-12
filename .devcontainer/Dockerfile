FROM nvidia/cuda:13.1.2-cudnn-devel-ubuntu24.04

ARG DEBIAN_FRONTEND=noninteractive

RUN apt update && apt-get install -y \
    python3 python3-pip python3-venv sudo git\
    && rm -rf /var/lib/apt/lists/* \
    && echo "ubuntu ALL=(root) NOPASSWD:ALL" > /etc/sudoers.d/ubuntu

USER ubuntu