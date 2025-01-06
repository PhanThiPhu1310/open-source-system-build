# Building An Open-Source System
## Overview
A comprehensive, open-source network infrastructure solution, leveraging virtual machines on CentOS and Ubuntu, integrates critical services including Samba, Bind, Zabbix, Apache, FTP, and Mail. This integrated system provides robust monitoring and management capabilities for a complete network environment.
## Key Features:
- Enhanced Collaboration: Seamless file sharing across the network with Samba.
- Reliable Communication: Robust DNS resolution with Bind for efficient communication.
- Internal Web Services: Host internal websites and applications with Apache.
- Comprehensive Email Support: Send and receive emails securely with Postfix and Dovecot.
- Proactive System Health: Monitor and manage system resources and performance with Zabbix.
- Dynamic Network Management: Efficiently manage IP addresses with DHCP.
## Installation
### System Requirements
- Virtualization Platform: VMware Workstation 
- Virtual Machines:
- 3 VMs with the following configurations:
  VM1 (CentOS 9): 2GB RAM, 20GB Disk
  VM2 (CentOS 9): 2GB RAM, 20GB Disk
  VM3 (Ubuntu): 2GB RAM, 20GB Disk
### Installation Steps
- Create Virtual Machines:
  Utilize VMware Workstation to create 3 virtual machines with the specified configurations.
- Install Operating Systems:
  Install CentOS 9 on VM1 and VM2, and Ubuntu on VM3.
  Refer to the official installation guides for each operating system for detailed instructions.
### System Architecture
This network infrastructure utilizes three virtual machines (VMs) to host a suite of essential services:
- VM1 (CentOS 9):
  File Sharing: Facilitates file sharing across the network using Samba.
  DNS Resolution: Provides reliable domain name resolution with Bind.
  System Monitoring: Enables proactive system monitoring and management with Zabbix.
- VM2 (CentOS 9_2):
  Web Hosting: Hosts internal websites and applications using Apache.
- VM3 (Ubuntu):
  File Transfer: Supports file transfers with an FTP server.
  Network Management: Manages IP address allocation dynamically using DHCP.
  Email Services: Provides comprehensive email capabilities with Postfix and Dovecot.
