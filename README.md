# DevOps Home Lab

This repository documents the design, deployment, and evolution of my personal DevOps home lab. The goal of this project is to build practical infrastructure engineering experience using virtualization, Linux servers, and automation tools.

This lab is being built incrementally as I progress through my studies in Information Technology and DevOps engineering.

Sensitive information such as internal IP addresses, credentials, and network identifiers are intentionally omitted from this documentation.

---

## Objectives

The goals of this home lab are to:

- Build hands-on experience with Linux server administration
- Practice infrastructure deployment and virtualization
- Learn DevOps tooling and workflows
- Document infrastructure decisions and system architecture
- Develop a professional portfolio demonstrating real systems work

---

## Core Technologies

Current technologies used in this lab include:

- Proxmox VE (Virtualization Platform)
- Ubuntu Server LTS
- Linux command-line administration
- SSH remote management
- GitHub for documentation and version control

Additional technologies will be added as the lab expands.

---

## Infrastructure Overview

Current lab structure:

    Internet
       |
    Home Router
       |
    Physical Lab Server
       |
    Proxmox VE Hypervisor
       |
    Ubuntu Server Virtual Machines


The hypervisor manages virtual machines used for infrastructure experimentation and service deployment.

---

## Lab Hardware

Physical server specifications are intentionally generalized for security reasons.

Typical configuration includes:

- Multi-core CPU
- Solid State Storage
- Minimum 32GB RAM
- Wired network connection

---

## Virtualization Platform

**Hypervisor:** Proxmox Virtual Environment

Proxmox is used to manage virtual machines and allocate compute resources for different lab environments.

Capabilities used:

- Virtual machine management
- Network bridging
- ISO image deployment
- Resource allocation
- Console access
- Snapshot capability

---

## Virtual Machines

### Ubuntu Server (Primary Lab VM)

Purpose: Linux administration practice and DevOps experimentation.

Configuration:

- Ubuntu Server LTS
- CLI-only installation (no graphical interface)
- SSH enabled for remote administration
- Hosted on Proxmox virtual infrastructure

Future roles for this VM may include:

- Web server hosting
- Container experimentation
- CI/CD testing
- Automation scripting

---

## Lab Progress Log

### Phase 1 – Infrastructure Setup

Completed:

- Installed Proxmox VE on dedicated server hardware
- Configured base networking and storage
- Accessed Proxmox web management interface
- Uploaded Ubuntu Server installation media

### Phase 2 – Virtual Machine Deployment

Completed:

- Created first Ubuntu Server VM
- Installed Ubuntu Server LTS
- Configured system hostname and user account
- Enabled SSH for remote administration

---

## Planned Future Work

Planned expansions for this lab include:

### Infrastructure

- Additional Linux virtual machines
- Network segmentation and virtual networks
- VM snapshots and backup strategy

### DevOps Tooling

- Docker containerization
- Infrastructure as Code experimentation
- CI/CD pipelines
- Configuration management tools

### Observability

- Monitoring stack deployment
- Log aggregation systems

### Automation

- Bash automation scripts
- Deployment workflows

---

## Documentation Philosophy

This repository serves as a technical journal of my infrastructure learning process.

Each major milestone in the lab will be documented, including:

- System configuration
- Deployment steps
- Lessons learned
- Architectural decisions

This allows the lab to function as both a learning environment and a professional portfolio.

---

## Security Notice

To protect the home network environment, the following information is intentionally excluded:

- Internal IP addresses
- Public IP addresses
- Credentials or authentication keys
- Network identifiers

All documentation is sanitized before publication.

---

## Author

Michael Matthews  
Information Technology Student  
Aspiring DevOps Engineer
