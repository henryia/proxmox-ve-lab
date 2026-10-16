# proxmox-ve-lab
Hands-on Proxmox VE lab on VMware ESXi 8.0, documenting clustering, Linux, storage, and automation.

**Author:** Henry Anchante  
**Focus:** Virtualization Engineering | Proxmox VE | VMware ESXi | Linux Infrastructure

## Project Overview

This repository documents a hands-on Proxmox VE laboratory deployed as nested virtualization on VMware ESXi 8.0, running on an HP Z640 workstation.

The objective is to explore enterprise virtualization, Linux administration, Proxmox clustering, storage technologies, infrastructure monitoring, and AI-assisted automation.

## Current Lab Infrastructure

| Node | vCPU | RAM | Local Disk |
|---|---:|---:|---:|
| PVE1 | 6 | 12 GB | 20 GB |
| PVE2 | 6 | 8 GB | 20 GB |
| PVE3 | 8 | 8 GB | 20 GB |

**Total allocated resources:** 20 vCPU, 28 GB RAM, 60 GB virtual disk capacity.

## Technology Stack

- VMware ESXi 8.0
- Proxmox Virtual Environment
- Linux
- Nested Virtualization
- Planned: Proxmox Clustering, ZFS, Ceph, Backup and Recovery, AI-assisted Infrastructure Automation

## Project Status

**Phase 1:** Three Proxmox VE virtual machines provisioned.

**Next phase:** Cluster configuration and validation.

## Documentation Roadmap

1. Lab architecture and environment preparation
2. Proxmox VE installation
3. Three-node cluster configuration
4. Linux networking and storage
5. ZFS and Ceph experiments
6. Backup and disaster recovery testing
7. AI-assisted infrastructure operations

## Professional Purpose

This project is part of my public infrastructure engineering portfolio, documenting practical technical work, configuration procedures, troubleshooting, and lessons learned.
