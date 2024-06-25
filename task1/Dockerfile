# Uses the 'latest' Ubuntu, more like 22.04

FROM ubuntu:22.04

# Specify the working directory

WORKDIR /app

# Update APT and upgrade current installed software

RUN apt-get update && apt-get install -y python3 python3-pip

# Install Flask api

RUN pip3 install flask

# Copy api.py to the working dir in container

COPY api.py /app/api.py

# Set command to run flask

CMD ["python3", "/app/api.py"]
