# Flask Application with Redis using Docker

This repository contains a Flask application that integrates with Redis, orchestrated with Docker for easy setup and deployment.

## Prerequisites

Ensure you have Docker installed on your machine:
- [Install Docker](https://docs.docker.com/get-docker/)

## Getting Started

Follow these steps to set up and run the application locally.

### Step 1: Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/your-repository.git
cd your-repository
```

### Step 2: Install Requirements

Install the required Python packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Step 3: Start Redis

Start Redis as a Docker container. If you haven't installed Redis, you can run it with Docker:

```bash
docker run -d --name my-redis -p 6379:6379 redis:alpine
```

### Step 4: Build and Run Docker Containers

Build and run the Docker containers using Docker Compose:

```bash
docker-compose up -d
```

### Step 5: Access the Application

Once the containers are running, access the Flask application in your web browser:

```
http://localhost:5000/
```

### Step 6: Stop the Application

To stop the containers and remove them (optional), run:

```bash
docker-compose down
```
