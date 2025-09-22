# Helm Apache App Trial

This repository contains a simple **Helm chart** to deploy an Apache HTTP server on a Kubernetes cluster.

## 📌 Prerequisites
- Kubernetes cluster (local with [Kind](https://kind.sigs.k8s.io/) or [Minikube](https://minikube.sigs.k8s.io/docs/))
- [Helm 3+](https://helm.sh/docs/intro/install/)

## 📂 Chart Structure
helm-apache-app-trial/

│── templates/ # Kubernetes manifest templates
│── Chart.yaml # Chart metadata
│── values.yaml # Default configuration values
│── .helmignore # Files ignored when packaging
