# workshop-docker-101
A workshop covering Docker fundamentals to jump start learning and practical challenges for real-life devops.


## Docker Fundamentals: Hands-on Workshop for Beginners and Beyond

This workshop will introduce attendees to Docker, the leading containerization platform, and equip them with the skills to build, run, and manage containerized applications. We'll cater to both beginners and experienced professionals, offering a solid foundation with bonus challenges for those who want to dig deeper.

## Target Audience:

- Developers, SysAdmins, and IT professionals with no prior Docker experience (Beginners)
- Professionals familiar with Docker who want to enhance their skills (Advanced)

## Prerequisites:

- Basic understanding of Linux commands (optional)

### Hardware/Software Requirements:

- Laptop with Docker installed (we'll provide installation instructions)
- Terminal access
- Code editor (optional)

## Workshop Outline:

### 1. Introduction to Containers and Docker (15 mins)

  - What are containers? Benefits of containerization
  - Introduction to Docker: Architecture, components (Docker daemon, client, image, container, registry)
  - **[Prerequisite]**[ Hands-on: Install and verify Docker setup](excercises/00-setup-docker/INSTALL.md)
  - **Bonus Challenge (Advanced):** Discuss use cases for containerization beyond development (e.g., micro-services, CI/CD pipelines)

> NOTE:
> For follwing steps we can use parts of official Docker [Getting started guide](https://github.com/docker/getting-started) and [Getting started app](https://github.com/docker/getting-started-app/).


### 2. Working with Docker Images (45 mins)

  - Docker Hub: Public registry for pre-built images
  - **[Prerequisite]** Pulling and running pre-built images (e.g., hello-world, a simple web server)
  - Hands-on: Pull and run a Docker image  (Beginners)
  - Exploring container details: `docker ps`, `docker inspect` (Beginners)
  - **Bonus Challenge (Advanced):** Build a simple Dockerfile from scratch

### 3. Deep Dive into Docker Commands (45 mins)

  - Common Docker commands: `docker run`, `docker stop`, `docker start`, `docker logs`, `docker exec`
  - Understanding options for running containers (detached mode, environment variables, port mapping)
  - Hands-on: Manage containers using various commands (Beginners)
  - **Bonus Challenge (Advanced):** Utilize volumes to persist data within containers
  - **Bonus Challenge (Advanced):** Explore Docker networks and link containers

### 4. Building and Sharing Docker Images (45 mins)

  - Introduction to Dockerfiles: The recipe for building custom images
  - Exploring a Dockerfile structure: Base image, instructions (COPY, RUN, CMD, etc.)
  - Building a simple Docker image from a Dockerfile (e.g., a Python web app)
  - Hands-on: Build and run a custom Docker image (Beginners)
  - Pushing images to Docker Hub (optional)
  - **Bonus Challenge (Advanced):** Multi-stage builds for creating smaller and optimized images

### 5. Introduction to Docker Compose (30 mins)

  - Managing multi-container applications with Docker Compose
  - Compose files: Defining services, networks, volumes for complex deployments
  - Hands-on: Deploy a multi-container application with Docker Compose (e.g., a simple web app with a database)
  - **Bonus Challenge (Advanced):** Discuss orchestration tools like Docker Swarm or Kubernetes

### 6. Q&A and Wrap-up (15 mins)

  - Open discussion for any questions or challenges faced during the workshop
  - Additional resources and next steps for learning Docker

### Bonus Materials:

- Provide a list of resources for further learning (Docker documentation, tutorials, online courses)
- Share example code repositories for the hands-on exercises
