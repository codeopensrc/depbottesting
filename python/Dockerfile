FROM python:3.13.4-alpine
RUN apk update && \
    apk upgrade && \
    apk add curl bash
### Current
COPY requirements.txt requirements.txt 
RUN pip3 install -r requirements.txt
