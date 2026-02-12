# CI/CD Pipeline using Git, Jenkins & Docker

## Project Overview
This project demonstrates a complete CI/CD pipeline to automate build and deployment of a static web application using GitHub, Jenkins, and Docker.

---

## Tools Used
- Git & GitHub
- Jenkins
- Docker
- AWS EC2
- Nginx (Base Image)

---

## Project Workflow

### Step 1: Create Application
Created a simple HTML application (index.html).

### Step 2: Push Code to GitHub
Initialized Git repository and pushed project files to GitHub.

### Step 3: Dockerfile Creation
Created Dockerfile using Nginx base image to containerize application.

### Step 4: Jenkins Setup
Installed Jenkins and configured GitHub integration.
Installed Docker & Git plugins.

### Step 5: Jenkins Pipeline
- Cloned code from GitHub
- Built Docker image
- Ran Docker container

### Step 6: Deployment
Application deployed on AWS EC2 and accessed via public IP and port.

---

## 📍 Output
Application successfully deployed using automated CI/CD pipeline.
