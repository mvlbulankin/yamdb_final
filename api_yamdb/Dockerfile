FROM python:3.7-slim

WORKDIR /app

COPY requirements.txt requirements.txt

RUN pip3 install -r api_yamdb/requirements.txt --no-cache-dir

COPY . .



