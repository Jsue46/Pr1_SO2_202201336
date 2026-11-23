# Operating Systems Virtualization and Linux Mint Environment

Academic project developed for the **Operating Systems 2** course at the Universidad de San Carlos de Guatemala (First Semester 2026).

This repository contains documentation, configuration specifications, and technical guides for deploying Debian-based GNU/Linux distributions in virtualized environments using VMware Workstation.

---

## Overview

The lab focuses on hypervisor architecture, hardware resource virtualization (CPU cores, RAM allocation, virtual disks, and NAT networking), operating system installation, user privilege segregation, and verification of Linux kernel parameters.

---

## Key Topics

- Type-2 hypervisor deployment and hardware virtualization principles
- Virtual machine provisioning: CPU core tuning, dynamic memory allocation, and virtual disk configuration
- Linux Mint (Debian-based) guest operating system installation from official ISO media
- User administration and POSIX permission management (superuser and standard accounts)
- Kernel inspection and runtime parameter validation (`uname -r`, hardware detection)
- NAT virtual network routing and host-guest communication verification

---

## Technical Specifications

- **Host Environment:** Windows 11
- **Hypervisor:** VMware Workstation
- **Guest OS:** Linux Mint (Debian Edition / Ubuntu LTS base)
- **Virtual Resources Allocated:** 2 vCPUs, 4 GB RAM, 40 GB Virtual Disk (SCSI/NVMe)
- **Network Mode:** NAT with dynamic DHCP reservation

---

## Repository Structure

```
Pr1_SO2_202201336/
├── Enunciado/                     # Course guidelines (PDF)
├── Manual/                        # Technical manual and screenshots (PDF)
└── README.md
```

---

## Academic Context

| Field       | Detail                                         |
|-------------|------------------------------------------------|
| Course      | Operating Systems 2 (SO2)                      |
| Institution | Universidad de San Carlos de Guatemala         |
| Semester    | First Semester 2026                            |
| Author      | Estuardo Josue Vaquiax Reyes (202201336)       |
