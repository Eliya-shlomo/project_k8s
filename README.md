# project_k8s

## Overview
This project demonstrates setting up a Kubernetes-based infrastructure using various best practices.  
It showcases how to deploy applications, manage resources, and orchestrate services within a Kubernetes cluster.

## Project Structure
- `deployment/` - YAML manifests for Kubernetes Deployments and Services
- `namespace/` - YAML configuration for Kubernetes Namespaces
- `configmap/` - Configuration files for Kubernetes ConfigMaps
- `ingress/` - Ingress rules and controllers configuration
- `secrets/` - YAML files for Kubernetes Secrets (base64 encoded)
- `storage/` - StorageClass, PVC (Persistent Volume Claim) configurations
- `README.md` - Documentation of the project

## Key Features
- Fully working Kubernetes deployment manifests.
- Modular structure: separate folders for ConfigMaps, Secrets, Deployments, and more.
- Ingress Controller setup for external traffic management.
- Best practices for separating environments (namespaces, secrets management).
- Examples of persistent storage usage with PVC and StorageClasses.

## Prerequisites
- Kubernetes Cluster (local using Minikube, Kind, or a cloud provider like EKS/GKE/AKS).
- `kubectl` CLI installed and configured.
- Basic knowledge of Kubernetes objects and architecture.
- Optional: Ingress Controller installed (like NGINX Ingress).

## How to Use

1. **Clone the repository**:

```bash
git clone https://github.com/Eliya-shlomo/project_k8s.git
cd project_k8s
