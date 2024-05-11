# python-docker-and-kubernetes

This repository contains the code and instructions for deploying a Python Flask application using Docker and Kubernetes. The lab is divided into two main sections: Docker and Kubernetes.

## Prerequisites

Before starting the lab, ensure that you have the following installed on your system:

- Docker
- Docker Desktop (with Kubernetes enabled)
- Python 3.x
- Git

## Docker Section

In this section, you will learn how to create a containerized Python application using Docker. Follow the steps outlined in the official Docker documentation: [Python Guide](https://docs.docker.com/language/python/).

1. Clone this repository to your local machine.
2. Navigate to the `docker` directory.
3. Follow the instructions in the Docker documentation to create a Docker image and run the containerized Python application.
4. Take screenshots of each step and paste them into a Microsoft Word document named `Docker-K8s-Lab.doc` under the "Docker" section.

## Kubernetes Section

In this section, you will deploy the Flask application you built in the Docker section on a Kubernetes cluster.

### Setting up Kubernetes

1. Install Kubernetes on your laptop using Docker Desktop. Follow the instructions to enable Kubernetes.
2. Go through the exercises in the official Kubernetes documentation: [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/).

### Deploying the Flask App

1. Create a Kubernetes Deployment with two pods for the Flask application.
2. Create a Kubernetes Service to expose the Flask application. You can use either ClusterIP or NodePort.
3. Take screenshots of each step and paste them into a separate "Kubernetes" section in the `Docker-K8s-Lab.doc` document.

## Submission

Once you have completed both sections and documented the steps with screenshots, submit the `Docker-K8s-Lab.doc` document using the file upload option in the assignment.

## Additional Resources

- [Docker Documentation](https://docs.docker.com/)
- [Kubernetes Documentation](https://kubernetes.io/docs/home/)
- [Flask Documentation](https://flask.palletsprojects.com/en/2.2.x/)
