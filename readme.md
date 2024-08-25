# HW3 Deployment Project

This project demonstrates a simple Node.js web application containerized with Docker and deployed on Kubernetes. The project includes additional features such as scaling the application using Kubernetes ReplicaSet and exposing it via an Ingress Controller.

## Project Structure

- **Dockerfile**: Defines the Docker image for the Node.js application.
- **deployment.yaml**: Kubernetes Deployment configuration for the application, including ReplicaSet for scaling.
- **service.yaml**: Kubernetes Service configuration for exposing the application internally in the cluster.
- **ingress.yaml**: Kubernetes Ingress configuration for routing external traffic to the application.

## Prerequisites

- Docker installed on your machine
- Kubernetes cluster set up (e.g., Minikube, Docker Desktop Kubernetes, etc.)
- `kubectl` installed and configured to interact with your Kubernetes cluster
- Docker Hub account
- Ingress Controller (e.g., NGINX Ingress Controller) deployed in your Kubernetes cluster

## Steps to Run the Application

### 1. Build the Docker Image

First, build the Docker image for the application:

```bash
docker build -t vasfidogan/hw3-deployment .

