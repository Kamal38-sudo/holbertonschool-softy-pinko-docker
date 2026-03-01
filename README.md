# Docker Learning Resources

This repository contains materials and examples for learning **Docker**, a platform for developing, shipping, and running applications inside containers.


##  What is Docker?

Docker is a **containerization platform** that allows you to package an application with all its dependencies into a standardized unit called a **container**.
Containers are **lightweight, portable, and isolated**, making it easy to run applications consistently across different environments.


##  Key Concepts

### 1. **Containers**
- Lightweight, executable packages including code, libraries, and runtime
- Isolated from the host system and other containers
- Ensure consistency across development, testing, and production

### 2. **Images**
- Read-only templates used to create containers
- Can be stored locally or in a registry (like Docker Hub)
- Built using a **Dockerfile** which defines instructions to create the image

### 3. **Dockerfile**
- Text file containing step-by-step instructions to build a Docker image
- Defines the base image, dependencies, environment variables, and commands

### 4. **Docker Hub**
- Public registry for sharing Docker images
- Can pull official images (like Python, Ubuntu, Nginx) or push your custom images

### 5. **Volumes**
- Persistent storage for containers
- Allows data to persist even if a container is removed

### 6. **Networks**
- Connect containers together or with external networks
- Isolate traffic between different applications


##  Getting Started

1. **Install Docker**
   - [Official Docker installation guide](https://docs.docker.com/get-docker/)

2. **Run your first container**
   ```bash
   docker run hello-world
