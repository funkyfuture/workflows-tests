FROM docker.io/python:3.9-alpine

RUN apk add --no-cache build-base cargo ca-certificates libffi-dev musl-dev openssl-dev python3-dev \
 && pip install cryptography
