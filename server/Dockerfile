# server/Dockerfile
FROM python:3.10-slim

WORKDIR /app

COPY server.py .

RUN pip install pillow

EXPOSE 8080

CMD ["python", "-u", "server.py"]

