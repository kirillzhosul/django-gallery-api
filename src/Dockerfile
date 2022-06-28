# syntax=docker/dockerfile:1
FROM python:3.10.4-alpine

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /api/gallery
COPY requirements.txt /api/gallery/

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

COPY . /api/gallery/