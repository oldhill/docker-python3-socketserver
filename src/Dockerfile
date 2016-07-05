# python:latest looks like debian jessie with latest python3 installed
FROM python:latest

# install nc to test out the socketserver with some TCP packets!
RUN apt-get update && apt-get install -y netcat-openbsd

WORKDIR app

COPY server.py app/

# CMD ["ls", "-al"]
CMD ["python3", "app/server.py"]
