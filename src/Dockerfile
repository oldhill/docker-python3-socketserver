# python:latest looks like debian jessie with latest python3 installed
FROM python:latest

WORKDIR app

COPY server.py app/

EXPOSE 9999

# CMD ["ls", "-al"]
CMD ["python3", "app/server.py"]
