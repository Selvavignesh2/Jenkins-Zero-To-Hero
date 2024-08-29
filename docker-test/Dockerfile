# Use an official lightweight Alpine Linux image
FROM alpine:latest

# Install Python and pip
RUN apk add --no-cache python3 py3-pip

# Set the working directory inside the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Run the Python app when the container launches
CMD ["python3", "-m", "http.server", "8082"]

