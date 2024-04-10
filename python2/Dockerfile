FROM python:3.12.3-alpine
RUN apk update && \
    apk upgrade && \
    apk add curl bash
### Outdated
COPY requirements.txt requirements.txt 
RUN pip3 install -r requirements.txt
