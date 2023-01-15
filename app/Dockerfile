FROM python:3.10.7-slim-buster

WORKDIR /usr/src/logger

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN pip install --upgrade pip
COPY requirements.txt /usr/src/logger/app/requirements.txt
RUN pip install -r /usr/src/logger/app/requirements.txt

COPY . /usr/src/logger/
