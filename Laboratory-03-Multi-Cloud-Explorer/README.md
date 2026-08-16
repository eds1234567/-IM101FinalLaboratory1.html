# Laboratory 03 – Multi-Cloud Explorer

## Mission Overview

This laboratory activity explores and compares three major public cloud platforms: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP). The activity focuses on their infrastructure, core services, advantages, and possible applications for different business requirements.

## Linux Server Investigation

A KillerCoda Linux Playground was used to investigate the basic information of a Linux server. The investigation focused on identifying the operating system, CPU information, memory, and available disk space.

### Linux Commands Used

The following Linux commands were used to collect the required information:

```bash
uname -a
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

## Based on the terminal output, the following information was collected:

* **Operating System:** Linux ubuntu 6.8.0-136-generic, x86_64, GNU/Linux
* **CPU Information:** 1 CPU, Intel Xeon E312xx (Sandy Bridge), 2.0GHz, x86_64 architecture
* **Memory:** 1.9Gi total, 469Mi used, 1.4Gi available
* **Disk Space:** 19G total, 5.4G used, 13G available (30% used)

### Cloud Services for Hosting the Linux Server

If the investigated Linux server were migrated to the cloud, equivalent virtual machine services could be used from each cloud provider.

| Cloud Provider        | Service                |
| --------------------- | ---------------------- |
| AWS                   | Amazon EC2             |
| Microsoft Azure       | Azure Virtual Machines |
| Google Cloud Platform | Compute Engine         |

These services provide virtual computing environments where Linux-based workloads can be deployed and managed in the cloud.

## Linux Investigation Screenshot

KillerCoda Terminal<img ![KillerCoda Terminal](https://github.com/user-attachments/assets/0ec6677d-5971-4cdf-98de-385563a06929)


## Mission Summary

Through this laboratory activity, AWS, Microsoft Azure, and Google Cloud Platform were explored and compared. Their services were also matched according to different categories such as computing, storage, networking, identity management, databases, and Kubernetes.

The activity demonstrates that cloud platform selection should be based on the specific requirements of an organization rather than popularity alone.
