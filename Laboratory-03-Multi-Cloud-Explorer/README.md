# Laboratory 03 – Multi-Cloud Explorer

## Mission Overview

This laboratory activity explores and compares three major public cloud platforms: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP). The activity focuses on their infrastructure, core services, advantages, and possible applications for different business requirements.

## Linux Server Investigation

A KillerCoda Linux Playground was used to investigate the basic information of a Linux server. The investigation focused on identifying the operating system, CPU information, memory, and available disk space.

### Linux Commands Used

The following Linux commands were used to collect the required information:

```bash
cat /etc/os-release
lscpu
free -h
df -h
```

### Information Collected

The terminal output was used to identify:

* Operating System
* CPU Information
* Memory
* Disk Space

### Cloud Services for Hosting the Linux Server

If the investigated Linux server were migrated to the cloud, equivalent virtual machine services could be used from each cloud provider.

| Cloud Provider        | Service                |
| --------------------- | ---------------------- |
| AWS                   | Amazon EC2             |
| Microsoft Azure       | Azure Virtual Machines |
| Google Cloud Platform | Compute Engine         |

These services provide virtual computing environments where Linux-based workloads can be deployed and managed in the cloud.

## Linux Investigation Screenshot

![KillerCoda Terminal](<img width="1899" height="1016" alt="killercoda-terminal png" src="https://github.com/user-attachments/assets/3aeb7e1a-3a8a-4ee9-9591-e9e764c460c4" />
)

## Mission Summary

Through this laboratory activity, AWS, Microsoft Azure, and Google Cloud Platform were explored and compared. Their services were also matched according to different categories such as computing, storage, networking, identity management, databases, and Kubernetes.

The activity demonstrates that cloud platform selection should be based on the specific requirements of an organization rather than popularity alone.
