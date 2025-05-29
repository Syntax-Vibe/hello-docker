# Simple Dockerized Python App

This is a basic Python application that prints a message to the terminal, packaged inside a Docker container.

## How to Run

1. Build the Docker image:
   ```
   docker build -t hello-docker .
   ```

2. Run the container:
   ```
   docker run hello-docker
   ```

Expected Output:
```
Hello from inside a Docker container!
```
