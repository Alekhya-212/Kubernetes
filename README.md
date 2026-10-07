# VProfile Kubernetes Project

This repository contains documentation and scripts to **create a Kubernetes cluster on AWS using kops** and **host the VProfile application**.

## Contents
- Scripts to set up AWS resources (EC2, IAM, S3, Route53)
- Instructions to install AWS CLI, kops, and kubectl
- Kubernetes manifests for deploying app, web, and database components
- Ingress controller configuration for load balancing
- Steps to configure DNS and access the hosted application

## Usage
1. Clone this repository into your EC2 kops instance:
   ```bash
   git clone https://github.com/Alekhya-212/vprokube.git
   cd vprokube
2. Follow the documentation to provision the cluster and deploy the application.

3. Once DNS is configured, access the application via your domain.
