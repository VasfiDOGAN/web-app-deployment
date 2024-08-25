# HW3 Deployment Project

This project demonstrates a simple Node.js web application containerized with Docker and deployed on Kubernetes.

## Project Structure

- **Dockerfile**: Defines the Docker image for the Node.js application.
- **deployment.yaml**: Kubernetes Deployment configuration for the application.
- **service.yaml**: Kubernetes Service configuration for exposing the application.

## Prerequisites

- Docker installed on your machine
- Kubernetes cluster set up (e.g., Minikube, Docker Desktop Kubernetes, etc.)
- kubectl installed and configured to interact with your Kubernetes cluster
- Docker Hub account

## Steps to Run the Application

### 1. Build the Docker Image

```bash
docker build -t vasfidogan/hw3-deployment .

