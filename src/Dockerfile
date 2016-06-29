# python:latest looks like debian jessie with latest python3 installed
FROM python:latest

WORKDIR app

COPY server.py app/

ENTRYPOINT ['python3', 'server.py']
