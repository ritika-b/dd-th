# Takehome Project

## Topic

This tutorial covers autoscaling using Amazon Web Services Elastic Kubernetes System (AWS EKS). Specifically, it will cover horizontal pod autoscaling (HPA) and using `kube-ops-view` as a tool to visualize Kubernetes clusters.

## Intended Audience

The appropriate audience for this guide would be experienced developers with basic Kubernetes and AWS service knowledge. The user should also have AWS Cloud Development Kit (CDK) knowdledge though they should be able to understand this tutorial without it. 

## Prerequisites

The user should take the following steps before proceeding with this guide:
- Install `eksctl`, a tool used for working with EKS clusters
- Install `yq` for YAML processing
- Install `kubectl` to interact with Kubernetes components
- Install `awscli` to work with AWS in the console
- Install `helm` to work with Kubernetes tools
- Launch EKS with a cluster successfully running on the service

