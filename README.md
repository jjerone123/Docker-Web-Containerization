# Docker Web Containerization

## Project Overview
Designed, built, and deployed a containerized web application using Docker Engine, Nginx, Ubuntu, and WSL 2.

## Technologies Used
- Docker Engine
- Nginx Alpine
- Ubuntu Linux
- WSL 2
- HTML and CSS
- GitHub

## Project Objectives
- Install and configure Docker Engine
- Build a custom Docker image
- Create and configure a Dockerfile
- Deploy a containerized web application
- Configure container port mapping
- Troubleshoot and verify deployment

## Deployment Instructions

Build the Docker image:

```bash
sudo docker build -t cloud-portfolio:v1 .
```

Deploy the container:

```bash
sudo docker run -d --name cloud-portfolio-web -p 127.0.0.1:8080:80 cloud-portfolio:v1
```

Verify the running container:

```bash
sudo docker ps
```

Access the application:

http://localhost:8080

## Deployment Evidence

### Custom Web Application
![Website](docker-portfolio-deployment.png)

### Running Docker Container
![Container](docker-container-running.png)

## Troubleshooting
Resolved Docker Desktop startup issues by implementing a lightweight Docker Engine environment using Ubuntu and WSL 2.

## Skills Demonstrated
- Containerization
- Linux administration
- Docker image management
- Application deployment
- Port mapping
- Technical troubleshooting
- DevOps fundamentals

## Project Status
Successfully deployed and tested.
