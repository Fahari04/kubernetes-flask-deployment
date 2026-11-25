
# Kubernetes Flask Application Deployment

A practical DevOps project demonstrating how to containerize
and deploy a Python Flask application using Docker and Kubernetes.

## Technology Stack

- Python 3.13
- Flask
- Gunicorn
- Docker
- Kubernetes
- Minikube
- GitHub Actions

## Project Architecture

Developer
    |
    v
GitHub Repository
    |
    v
GitHub Actions CI
    |
    v
Automated Python Tests
    |
    v
Docker Image
    |
    v
Kubernetes Deployment
    |
    v
Kubernetes Service
    |
    v
Flask Application

## Application Endpoints

| Endpoint | Purpose |
|----------|---------|
| / | Application welcome message |
| /health | Health check |

## Kubernetes Resources

- Deployment
- Service
- ConfigMap
- Secret
- Readiness Probe
- Liveness Probe

## Local Development

Install dependencies:

    py -m pip install -r app/requirements.txt

Run application:

    py app/app.py

Run tests:

    py -m unittest discover -s tests -v

## Kubernetes Deployment

Build and deploy instructions will be added
after the Docker image is built and tested.

## Project Status

Initial application and infrastructure configuration
prepared. Testing and deployment are pending.
