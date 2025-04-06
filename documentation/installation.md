# Installation Guide

This guide provides step-by-step instructions for setting up the Secure Linux File Server.

## Prerequisites

- CentOS 9 or equivalent (Rocky Linux, AlmaLinux)
- Root or sudo access
- Internet connection for package installation

## Step 1: Initial System Setup

```bash
# Update the system
sudo dnf update -y

# Install essential packages
sudo dnf install -y vim nano wget curl net-tools firewalld bash-completion

# Run the file server setup script
sudo ./scripts/setup_file_server.sh

# Run the web interface setup script
sudo ./scripts/setup_web_interface.sh

# Web Access
http://YOUR_SERVER_IP/fileserver/

