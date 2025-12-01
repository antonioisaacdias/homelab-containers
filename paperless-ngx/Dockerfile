FROM ghcr.io/paperless-ngx/paperless-ngx:latest

USER root

RUN apt-get update && \
    apt-get install -y tesseract-ocr-por && \
    apt-get clean

USER paperless
