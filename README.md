# SIT323 - Cloud Native Application Development

## Project Overview
This project demonstrates how to containerize a simple Node.js application using Docker and deploy it on a Kubernetes cluster. The application is built using **Express.js** and serves a "Hello, Docker!" message. It is packaged in a Docker container and deployed to Kubernetes for orchestration.

### Key Features:
- **Dockerized Node.js Application**: The app is packaged in a Docker container.
- **Kubernetes Deployment**: The app is deployed on a Kubernetes cluster with automated scaling and management.
- **NodePort Service**: Exposes the application through a NodePort service, making it accessible externally.
  
## Technologies Used:
- **Node.js**: JavaScript runtime used to build the application.
- **Docker**: Used to containerize the Node.js application.
- **Kubernetes**: A container orchestration platform to deploy, manage, and scale the containerized app.
- **kubectl**: Command-line tool used to interact with the Kubernetes cluster.

## Project Structure
- **Dockerfile**: Contains instructions to build the Docker image.
- **server.js**: Main application file that starts the Node.js server.
- **package.json**: Defines dependencies and project configuration for the Node.js application.
- **deployment.yaml**: Kubernetes deployment configuration for deploying the application.
- **service.yaml**: Kubernetes service configuration to expose the application.


