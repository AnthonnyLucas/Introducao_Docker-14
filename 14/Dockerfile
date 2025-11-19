FROM ubuntu:focal

RUN apt-get update && \
    apt-get install -y python3 && \
    rm -rf /var/lib/apt/lists/*

WORKDIR /app

COPY process.py .

CMD ["python3", "process.py"]
