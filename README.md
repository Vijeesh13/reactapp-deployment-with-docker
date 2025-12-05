⭐ Project Summary

I developed a simple React single-page application and deployed it using a Docker multi-stage build with Nginx as the production server.
To simulate a real DevOps environment, I integrated a complete CI/CD pipeline using Jenkins, Docker Hub, and automated shell scripts for server setup and deployment.

This project highlights my understanding of DevOps workflows, containerization, and deployment automation.

🧩 Key Responsibilities / What I Built
1. Frontend Application (React)

Designed a simple SPA with React components and routing.

Configured production build optimizations.

2. Docker Containerization

Created a multi-stage Dockerfile:

Stage 1: Build React app using Node

Stage 2: Serve static files using Nginx

Produced lightweight and secure production images.

3. CI/CD Pipeline with Jenkins

Built a Jenkins pipeline that:

Pulls the latest source code

Builds the Docker image

Logs into Docker Hub

Pushes tagged images to the registry

Demonstrated CICD understanding: automation, versioning, environment consistency.

4. Deployment Automation

Developed scripts to:

Install Java, Docker, and Jenkins on an Ubuntu server

Build, run, and push Docker images

Enabled seamless setup of new environments.
