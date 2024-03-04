# syntax=docker/dockerfile:1
FROM python:3.9-slim-buster
WORKDIR /server
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . .
# CMD ["python3", "server.py"]