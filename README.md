# Terraform Lab Week 4

## Overview
This repository contains the Terraform configuration and cloud-init script to launch an EC2 instance in AWS using a custom SSH key pair, with Nginx and Nmap installed via cloud-init.

## SSH Key Generation
To create a new SSH key pair:
```bash
ssh-keygen -t rsa -b 4096 -C "web-user"
