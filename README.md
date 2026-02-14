# ansible-webserver-apache-hardening
Infrastructure as Code project that automates the deployment, configuration, and security hardening of Apache web servers using Ansible. Includes SSL certificate management, firewall configuration (UFW), security updates, and multi-host support.

## 📌 Project Overview
This project automates the deployment and security hardening of Apache web servers using Ansible.

## 🚀 Features
- Apache2 installation
- Security modules enabled (SSL, headers, rewrite)
- UFW firewall configuration
- Self-signed SSL certificate generation
- Automated security updates
- Certificate management playbook

## 🖥️ Infrastructure
- Linux Mint server
- Ubuntu server
- Apache2
- Ansible

## ▶️ Run Playbook

```bash
ansible-playbook -i inventory.ini secure_webserver.yml
ansible-playbook -i inventory.ini security_updates.yml
ansible-playbook -i inventory.ini ssl_cert_management.yml

