# DevOps End-to-End Platform

![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Terraform](https://img.shields.io/badge/Terraform-IaC-purple)
![Docker](https://img.shields.io/badge/Docker-Containers-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blue)
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-orange)
![Grafana](https://img.shields.io/badge/Grafana-Dashboards-orange)
![Ansible](https://img.shields.io/badge/Ansible-Automation-red)

## Overview

This project demonstrates a complete modern DevOps workflow from source code management to deployment, monitoring, infrastructure provisioning, and configuration management.

The platform integrates cloud infrastructure, containerization, CI/CD pipelines, orchestration, monitoring, and automation into a single end-to-end DevOps environment.

The objective was to build a practical DevOps platform using industry-standard tools rather than isolated technology demonstrations.

---

## Business Problem

Modern applications require reliable infrastructure, automated deployments, monitoring, and operational visibility.

This project demonstrates how a DevOps engineer can:

* Provision infrastructure
* Deploy applications
* Automate workflows
* Monitor systems
* Visualize metrics
* Automate server configuration

using modern cloud-native technologies.

---

## Architecture

<img width="166" height="1811" alt="Architecture-Diagram drawio" src="https://github.com/user-attachments/assets/8ef1ee5d-3983-45bb-a753-b66879df4d14" />


---

## Technology Stack

### Cloud & Infrastructure

* AWS EC2
* Terraform
* Linux

### Containers & Orchestration

* Docker
* Kubernetes

### CI/CD

* Git
* GitHub
* GitHub Actions

### Monitoring & Observability

* Prometheus
* Grafana

### Automation

* Ansible

---

## Project Outcomes

* Provisioned AWS cloud infrastructure using Terraform
* Built automated CI/CD pipelines using GitHub Actions
* Containerized applications using Docker
* Deployed workloads using Kubernetes
* Implemented monitoring using Prometheus
* Visualized metrics using Grafana dashboards
* Automated Linux server configuration using Ansible
* Documented over 70 implementation screenshots
* Built a complete end-to-end DevOps workflow

---

## Project Components

### Application And CI Source

Merged implementation files are included in this repository so the screenshots are backed by source-controlled project work.

**Key files:**

* `app/docker-webapp/Dockerfile`
* `app/docker-webapp/index.html`
* `.github/workflows/docker-webapp.yml`
* `docs/docker-webapp-project-summary.md`

**Skills:**

* Dockerfile authoring
* Static web app containerization
* GitHub Actions workflow configuration
* Docker image build validation

---

### Linux Administration Lab

Built and managed Linux servers using SSH, package management, permissions, processes, and services.

**Skills:**

* Linux Administration
* SSH
* System Management
* Troubleshooting

---

### Docker Web Application

Created Docker images and deployed Nginx containers using Dockerfiles, networking, and volume mounts.

**Skills:**

* Docker
* Dockerfiles
* Containers
* Networking

---

### AWS Deployment

Provisioned and managed public-facing EC2 infrastructure and deployed containerized applications.

**Skills:**

* AWS EC2
* Security Groups
* Cloud Networking
* Linux Servers

---

### Terraform Infrastructure

Created Infrastructure as Code workflows using Terraform to provision AWS resources.

**Skills:**

* Terraform
* Infrastructure as Code
* State Management
* Cloud Automation

---

### GitHub Actions CI/CD

Implemented automated build pipelines triggered from GitHub commits.

**Skills:**

* GitHub Actions
* CI/CD
* YAML
* Automation

---

### Kubernetes Homelab

Deployed and managed applications using Deployments, Pods, and Services.

**Skills:**

* Kubernetes
* Deployments
* Pods
* Services
* kubectl

---

### Monitoring Stack

Installed and configured Prometheus and Grafana for metrics collection and visualization.

**Skills:**

* Prometheus
* Grafana
* Monitoring
* Observability
* Dashboards

---

### Ansible Automation

Automated Linux server configuration using Ansible inventories and playbooks.

**Skills:**

* Ansible
* Playbooks
* Configuration Management
* Server Automation

---

## Skills Demonstrated

* Linux Administration
* Infrastructure as Code
* Cloud Infrastructure
* CI/CD
* Containerization
* Kubernetes Administration
* Monitoring & Observability
* Configuration Management
* Automation
* Troubleshooting
* Documentation
* Cloud Operations

---

## Project Gallery

The screenshot evidence is organized as an ordered lab sequence. The folder names follow the same progression as the implementation screenshots, so reviewers can scan the project from fundamentals through the final end-to-end result.

| Lab | Screenshot range | Evidence |
| --- | --- | --- |
| 01 - Linux and Git Foundations | 01-06 | [Screenshots/01-linux-git-foundations](Screenshots/01-linux-git-foundations) |
| 02 - Docker Web App Containerization | 07-17 | [Screenshots/02-docker-webapp-containerization](Screenshots/02-docker-webapp-containerization) |
| 03 - AWS EC2 Cloud Deployment | 19-26 | [Screenshots/03-aws-ec2-cloud-deployment](Screenshots/03-aws-ec2-cloud-deployment) |
| 04 - Terraform Infrastructure as Code | 27-49 | [Screenshots/04-terraform-infrastructure-as-code](Screenshots/04-terraform-infrastructure-as-code) |
| 05 - GitHub Actions CI/CD | 36-39 | [Screenshots/05-github-actions-ci-cd](Screenshots/05-github-actions-ci-cd) |
| 06 - Project Evidence Library | 50 | [Screenshots/06-project-evidence-library](Screenshots/06-project-evidence-library) |
| 07 - AWS Terraform EC2 Verification | 51 | [Screenshots/07-aws-terraform-ec2-verification](Screenshots/07-aws-terraform-ec2-verification) |
| 08 - Kubernetes Minikube Orchestration | 52-64 | [Screenshots/08-kubernetes-minikube-orchestration](Screenshots/08-kubernetes-minikube-orchestration) |
| 09 - Prometheus and Grafana Monitoring | 65-71 | [Screenshots/09-prometheus-grafana-monitoring](Screenshots/09-prometheus-grafana-monitoring) |
| 10 - Ansible Configuration Management | 72-74 | [Screenshots/10-ansible-configuration-management](Screenshots/10-ansible-configuration-management) |
| 11 - End-to-End Project Overview | 75 | [Screenshots/11-end-to-end-project-overview](Screenshots/11-end-to-end-project-overview) |

---

## Documentation

This repository contains over 70 implementation screenshots demonstrating:

* Infrastructure provisioning
* Docker deployments
* AWS deployments
* Terraform workflows
* CI/CD pipelines
* Kubernetes deployments
* Monitoring implementation
* Ansible automation
* Troubleshooting and issue resolution

### Screenshot Evidence Index

| Ordered lab | Evidence |
| --- | --- |
| 01 - Linux and Git Foundations | [Screenshots/01-linux-git-foundations](Screenshots/01-linux-git-foundations) |
| 02 - Docker Web App Containerization | [Screenshots/02-docker-webapp-containerization](Screenshots/02-docker-webapp-containerization) |
| 03 - AWS EC2 Cloud Deployment | [Screenshots/03-aws-ec2-cloud-deployment](Screenshots/03-aws-ec2-cloud-deployment) |
| 04 - Terraform Infrastructure as Code | [Screenshots/04-terraform-infrastructure-as-code](Screenshots/04-terraform-infrastructure-as-code) |
| 05 - GitHub Actions CI/CD | [Screenshots/05-github-actions-ci-cd](Screenshots/05-github-actions-ci-cd) |
| 06 - Project Evidence Library | [Screenshots/06-project-evidence-library](Screenshots/06-project-evidence-library) |
| 07 - AWS Terraform EC2 Verification | [Screenshots/07-aws-terraform-ec2-verification](Screenshots/07-aws-terraform-ec2-verification) |
| 08 - Kubernetes Minikube Orchestration | [Screenshots/08-kubernetes-minikube-orchestration](Screenshots/08-kubernetes-minikube-orchestration) |
| 09 - Prometheus and Grafana Monitoring | [Screenshots/09-prometheus-grafana-monitoring](Screenshots/09-prometheus-grafana-monitoring) |
| 10 - Ansible Configuration Management | [Screenshots/10-ansible-configuration-management](Screenshots/10-ansible-configuration-management) |
| 11 - End-to-End Project Overview | [Screenshots/11-end-to-end-project-overview](Screenshots/11-end-to-end-project-overview) |

---

## Supporting Labs

Additional learning artifacts from earlier DevOps practice repositories were merged into [labs/](labs/). These files show the foundation behind the flagship project, including Linux notes, Git notes, SSH setup, and early lab documentation.

---

## Key DevOps Concepts Demonstrated

* Infrastructure as Code (IaC)
* Continuous Integration (CI)
* Continuous Delivery (CD)
* Containerization
* Cloud Computing
* Kubernetes Orchestration
* Monitoring & Observability
* Configuration Management
* Automation
* DevOps Best Practices

---

## Future Improvements

* Multi-environment deployments
* Automated Kubernetes deployments
* Advanced monitoring dashboards
* Infrastructure scaling
* Additional cloud services

---

## Author

**Vitorino Gomes**

Computer Programming Student
Aspiring DevOps Engineer

Technologies:
AWS | Terraform | Docker | Kubernetes | GitHub Actions | Prometheus | Grafana | Ansible
