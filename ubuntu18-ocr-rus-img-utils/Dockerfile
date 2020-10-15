FROM ubuntu:18.04
MAINTAINER jentlemanjux
RUN apt-get -qq update && apt-get -y install ghostscript imagemagick poppler-utils \
  tesseract-ocr tesseract-ocr-rus \
  && apt-get autoclean \
  && rm -rf /var/lib/apt/lists/*
