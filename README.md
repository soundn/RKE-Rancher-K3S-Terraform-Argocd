
# Deploying Argocd on a Rancher-Managed K3S Cluster with RKE Kubernetes Using Terraform and Helm

## Introduction
This project demonstrates the deployment of Argocd on a Rancher-managed K3S cluster with RKE Kubernetes using Terraform and Helm. The setup involves creating virtual machines, installing RKE Kubernetes, and utilizing Rancher to manage the cluster.

## Prerequisites
- Two cloud-based virtual machines
- Installed RKE Kubernetes on both VMs
- Rancher for cluster management
- Terraform for infrastructure automation
- Helm for managing Kubernetes applications
- Argocd for codntinous deployment

## Steps

### 1. Creating VMs
1. Create two virtual machines on your preferred cloud provider.

### 2. Installing RKE Kubernetes
1. Install RKE Kubernetes on both VMs.

### 3. Setting Up Rancher
1. Install Rancher on the VMs.
2. Launch the Rancher UI.
3. Create a K3S cluster using Rancher.

### 4. Installing Helm
1. Install Helm on the VMs where RKE Kubernetes is installed.

### 5. Deploying Argocd with Terraform
1. Write a Terraform script to deploy Argocd on the K3S cluster.
2. Execute the Terraform script to deploy Argocd.

### 6. Using Helm Charts
1. Utilize Helm charts to deploy applications in  Argocd.

## Conclusion
This README provides a comprehensive guide to deploying Argocd on a Rancher-managed K3S cluster with RKE Kubernetes using Terraform and Helm.
