> [!NOTE]
> This repository is deliberately kept bare with simple outline and prequisites. We will update it with all hands-on labs near the workshop date.

# Docker Workshop
A workshop covering Docker fundamentals to jump start learning and practical challenges for real-life devops.

## Docker Fundamentals: Hands-on Workshop for Beginners and Beyond

This workshop will introduce attendees to Docker, the leading containerization platform, and equip them with the skills to build, run, and manage containerized applications. We'll cater to both beginners and experienced professionals, offering a solid foundation with bonus challenges for those who want to dig deeper.

## Target Audience:

- Developers, SysAdmins, and IT professionals with no prior Docker experience (Beginners)
- Professionals familiar with Docker who want to enhance their skills (Advanced)

## Prerequisites:

- Basic understanding of your preferred terminal
- Basic familiarity with development in any programming language (Python, Javascript, Golang, Java etc.)
- Laptop* with good battery backup

> You can share one laptop among 2-3 participants and work together. Actually, that is the recommended approach to learn.

### Hardware/Software Requirements:

- Laptop with Docker Desktop[1] installed. Check [Official Installation Guides](https://docs.docker.com/get-docker/)
- Terminal access (Windows Terminal on Win10/11, Bash/Zsh/Fishshell on Mac/Linux)
- [Sign Up for a FREE Docker Hub account](https://hub.docker.com/signup), only if not done already while Docker Desktop setup
- Code editor (optional)

> [!IMPORTANT]
> 1. On some Linux distributions you may have Docker Engine (Docker CE) and CLI installed instead of Docker Desktop. That is perfectly fine. If you have Docker Desktop installed then it comes bundled with Docker Engine and CLI.
> 2. Setting up Docker on Windows can be tedious and confusing. Reach out to us by creating an issue in the repository if you face any difficulties.

## Workshop Outline:

### 1. Introduction to Containers and Docker

  - What are containers? Benefits of containerization
  - Introduction to Docker: Architecture, components (Docker daemon, client, image, container, registry)
  - **Bonus Challenge (Advanced):** Discuss use cases for containerization beyond local development (e.g., micro-services, CI/CD pipelines)

### 2. Working with Docker Images

  - Docker Hub: Public registry for pre-built images
  - **[Prerequisite]** Pulling and running pre-built images (e.g., hello-world, a simple web server)
  - Hands-on: Pull and run a Docker image  (Beginners)
  - Exploring container details: `docker ps`, `docker inspect` (Beginners)
  - **Bonus Challenge (Intermediate):** Build a simple Dockerfile from scratch to package a web app

### 3. Deep Dive into Docker Command

  - Common Docker commands: `docker run`, `docker stop`, `docker start`, `docker logs`, `docker exec`
  - Understanding options for running containers (detached mode, environment variables, port mapping)
  - Hands-on: Manage containers using various commands (Beginners)
  - **Bonus Challenge (Intermidiate):** Utilize volumes to persist data within containers
  - **Bonus Challenge (Advanced):** Explore Docker networks and link containers

### 4. Building and Sharing Docker Images

  - Introduction to Dockerfiles: The recipe for building custom images
  - Exploring a Dockerfile structure: Base image, instructions (COPY, RUN, CMD, etc.)
  - Building a simple Docker image from a Dockerfile (e.g., a Python web app)
  - Hands-on: Build and run a custom Docker image (Beginners)
  - Pushing images to Docker Hub (optional)
  - **Bonus Challenge (Intermediate):** Multi-stage builds for creating smaller and optimized images
  - **Bonus Challenge (Advanced):** Security best practices for Dockerfile

### 5. Introduction to Docker Compose

  - Managing multi-container applications with Docker Compose
  - Compose files: Defining services, networks, volumes for complex deployments
  - Hands-on: Deploy a multi-container application with Docker Compose (e.g., a simple web app with a database)
  - **Bonus Challenge (Advanced):** Discuss orchestration tools like Docker Swarm or Kubernetes

### 6. Q&A and Wrap-up (15 mins)

  - Open discussion for any questions or challenges faced during the workshop
  - Additional resources and next steps for learning Docker
