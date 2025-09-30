# K8s-Kind-Voting-Application
A comprehensive guide for setting up a Kubernetes cluster using Kind on an AWS EC2 instance, installing and configuring Argo CD, and deploying applications using Argo CD.

# Overview
This guide covers the steps to:

-Launch an AWS EC2 instance.
-Install Docker and Kind.
-Create a Kubernetes cluster using Kind.
-Install and access kubectl.
-Set up the Kubernetes Dashboard.
-Install and configure Argo CD.
-Connect and manage your Kubernetes cluster with Argo CD.

#Architecture
<img width="1036" height="502" alt="image" src="https://github.com/user-attachments/assets/41dfd2cd-9dc0-4220-a164-fbc110112d5a" />

#Observability

<img width="1920" height="1080" alt="Screenshot 2025-09-30 195031" src="https://github.com/user-attachments/assets/043efa52-f86d-4e93-ad4a-7773396ffe71" />
<img width="1920" height="1080" alt="Screenshot 2025-09-30 192814" src="https://github.com/user-attachments/assets/7d1b2c31-d446-45c3-bfc6-ea71be4b900c" />
<img width="1920" height="1080" alt="Screenshot 2025-09-30 193859" src="https://github.com/user-attachments/assets/9c3df30e-e898-46ba-99d7-fdaf16d28085" />

-A front-end web app in Python which lets you vote between two options
-A Redis which collects new votes
-A .NET worker which consumes votes and stores them in…
-A Postgres database backed by a Docker volume
-A Node.js web app which shows the results of the voting in real time

#Key Technologies:

-AWS EC2: Infrastructure hosting for Kubernetes clusters.
-Kubernetes Dashboard: User-friendly interface for managing containerized applications.
-Argo CD: Continuous Delivery tool for automated application deployments.
