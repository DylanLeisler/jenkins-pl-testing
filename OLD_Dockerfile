FROM python:3.6-alpine
RUN apk add g++ jpeg-dev zlib-dev libjpeg make
RUN pip3 install matplotlib

COPY ./python-test-app ./myfolder

RUN python3 ./myfolder/main.py