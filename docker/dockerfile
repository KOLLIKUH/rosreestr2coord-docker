FROM python:2.7-slim

RUN mkdir -p /rosreestr2coord
RUN apt update && apt install mc libglib2.0-0 libsm6 libxext6 libxrender1 -y
WORKDIR /rosreestr2coord
COPY requirements.txt .
RUN pip install -r requirements.txt
