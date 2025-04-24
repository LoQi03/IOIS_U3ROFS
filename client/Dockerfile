# client/Dockerfile
FROM python:3.10-slim

WORKDIR /app

COPY client.py .
COPY sample.bmp sample.bmp

RUN pip install requests

CMD ["python", "client.py"]