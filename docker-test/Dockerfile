# Dockerfile
FROM alpine:latest

# Install dependencies
RUN apk add --no-cache python3 py3-pip

# Copy a Python script (if any) into the container
COPY hello.py /app/hello.py

# Set the working directory
WORKDIR /app

# Command to run the Python script
CMD ["python3", "hello.py"]

