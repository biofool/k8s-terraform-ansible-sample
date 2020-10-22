<div align="center" id="overwatch">
    <img src="./assets/kubesat.svg" alt="Overwatch" height="128px">
</div>

# <div align="center">Mini Challenge 1</div>

Deploy [Kubernetes](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/) on [AWS](https://docs.aws.amazon.com/) manually using [Terraform](https://www.terraform.io/docs/index.html) and [Ansible](https://docs.ansible.com/ansible/latest/index.html). Setup a monitoring solution using [Prometheus](https://prometheus.io/docs/prometheus/latest/getting_started/) and [Grafana](https://grafana.com/docs/) to gain oversight of the deployment.

## Introduction

Deploying Kubernetes the 'hard way' using Terraform and Ansible allows the developer to exercise more control over their cluster(s). It is also significantly cheaper than using a managed service such as [Amazon EKS](https://aws.amazon.com/eks/pricing/).

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. Configuration files describe to Terraform the components needed to run an application. Terraform generates an execution plan to reach the desired state, and then executes it to build the described infrastructure.

Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates.

A monitoring solution comprised of Prometheus and Grafana provides the developer with more insight into their cluster's performance.

## System Diagram

<div align="center">
    <img src="./assets/systemDiagram.png" width="600px" alt="system diagram">
    <p>System Diagram</p>
</div>

## Demo

<div align="center">
    <img src="./assets/dashboard.png" width="600px" alt="dashboard">
    <p>Grafana</p>
</div>

## Setup

The comprehensive set of setup instructions can be found in [`setup.md`](setup.md)

## Contributors

-   [Adam Alston](https://github.com/adamalston)
-   [Kenneth Kron](https://github.com/biofool)
-   [Zachari Ramos](https://github.com/zramos2)
-   [Hari Ravichandran](https://github.com/hariravichandran)
-   [Anthony Galassi](https://github.com/bendhouseart)
