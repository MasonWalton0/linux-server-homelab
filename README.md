##Project Overview
This project simulates the setup and hardening of a real Linux server environment inside a virtual machine. The lab focuses on foundational infrastructure and cybersecurity concepts including user management, SSH remote access, firewall configuration, and system updates.
The goal was to gain practical Linux administration experience commonly used in cybersecurity, cloud engineering, DevOps, and IT infrastructure roles.

##Technologies Used
Tool	Purpose
Oracle VirtualBox / VMware	Virtualization platform
Ubuntu Server	Linux server operating system
OpenSSH Server	Secure remote administration
UFW Firewall	Linux firewall management
Linux Terminal	System administration
APT Package Manager	Software installation and updates
Network Architecture
┌─────────────────────────────────────────────┐
│             Virtual Lab Network             │
│                                             │
│               UBUNTU-SERVER                 │
│               Ubuntu Server VM              │
│                                             │
│      SSH Access + Firewall + Users          │
└─────────────────────────────────────────────┘
The Linux server runs inside a virtual machine and is configured similarly to real-world enterprise Linux servers used in cloud and cybersecurity environments.
---
##Phase 1 — Linux Server Deployment
  #What Was Built
    Installed Ubuntu Server inside a virtual machine
    Configured initial server setup
    Updated system packages
    Verified network connectivity
    Learned core Linux terminal navigation and administration
    
  #Key Skills Demonstrated
    Linux server installation
    Virtual machine management
    Package management with APT
    Linux command-line usage
    Basic networking verification
---
##Phase 2 — User & Permission Management
  #What Was Built
    Created additional Linux user accounts
    Configured sudo administrative permissions
    Learned Linux file and user permission structure
    Practiced account management commands
 
  #Commands Used
    sudo adduser john
    sudo usermod -aG sudo john
    
  #Key Skills Demonstrated
    Linux user administration
    Privilege management
    Group permissions
    Principle of least privilege
---
##Phase 3 — SSH Remote Access Configuration
  #What Was Built
    Installed and enabled OpenSSH Server
    Verified SSH service status
    Configured remote server access
   Practiced secure remote administration
  
  #Commands Used
    sudo apt install openssh-server
    sudo systemctl status ssh

  #Key Skills Demonstrated
    SSH configuration
    Remote Linux administration
    Service management with systemctl
    Secure server access practices
---
##Phase 4 — Firewall Configuration & Security Hardening
  #What Was Built
    Installed and configured UFW firewall
    Allowed SSH traffic through firewall
    Enabled firewall protection
    Verified firewall rules

  #Commands Used
    sudo ufw allow ssh
    sudo ufw enable
    sudo ufw status

  #Key Skills Demonstrated
    Linux firewall administration
    Port management
    Network security basics
    Security hardening practices
---
##Phase 5 — System Updates & Maintenance
  #What Was Built
    Updated installed packages
    Upgraded system software
    Practiced vulnerability patch management
    Learned importance of system maintenance

  #Commands Used
    sudo apt update
    sudo apt upgrade

  #Key Skills Demonstrated
    Linux patch management
    System maintenance
    Security update procedures
    Vulnerability mitigation
---
##Key Concepts Covered
  Linux Administration — managing users, services, and system resources
  SSH Remote Access — securely connecting to remote systems
  Firewall Security — controlling inbound network traffic
  Privilege Management — assigning administrative permissions securely
  Patch Management — keeping systems updated against vulnerabilities
  Infrastructure Security — hardening systems against unauthorized access
---
##Lab Environment Specs
  VM	OS	RAM	Disk
  UBUNTU-SERVER	Ubuntu Server	2GB	25GB
