# 🖥️ Homelab Infrastructure Lab

## Overview
I designed and maintain a **virtualized datacenter homelab** to simulate enterprise infrastructure.  
This lab helps me practice real-world **systems administration, networking, automation, and security** skills.

## 🎯 Why I Built This Homelab

I enjoy the process of taking an empty server and building it up into a fully functional environment.  
My goal was to create a set of utilities I use on a daily basis while also practicing skills that mirror the responsibilities I’d face in an enterprise job environment.  

This homelab allows me to:
- Continuously expand and improve my setup, seeing real progress over time  
- Run practical tools I rely on every day (file sharing, password management, monitoring, VPN access)  
- Gain hands-on experience with the same technologies used in professional IT environments  
- Experiment safely with automation, security, and networking concepts before applying them in production-like scenarios  

---

## 🌐 Network Topology

- VLANs for **Management, Proxmox, and Lab/Test traffic**  
- **OPNsense** VM for advanced firewalling, routing, and segmentation  
- Remote access secured with **TailScale VPN**

📷 *Add a **diagram of your network topology** here (router → switch → Proxmox → VMs/VLANs).*  
Example:  
`![Network Diagram](images/network-diagram.png)`

---

## ⚙️ Virtual Machines & Services
- **Proxmox Backup Server** – Automated VM/container snapshots & disaster recovery  
- **TrueNAS (ZFS)** – Storage & backup server for shared files and VM data  
- **NextCloud** – Self-hosted collaboration and file sync  
- **VaultWarden** – Password manager for secure credential storage  
- **Nginx Proxy Manager** – Reverse proxy with SSL termination  
- **Docker Host** – Containerized apps & microservices testing  
- **Pi-hole** – Network-wide DNS filtering and ad blocking  
- **Zabbix** – Infrastructure monitoring and alerting  
- **Centralized Log Monitoring** – Aggregated logs for observability  
- **ServerHosting VM** – General-purpose testing environment  
- **Infra-Control Node** – Automation workflows (Ansible/Terraform)

📷 *Add a **screenshot of your Proxmox VM/container list** here.*  
Example:  
`![Proxmox VM Overview](images/proxmox-vms.png)`

👉 *(Optional: for each major service, add a short note on what you learned. Example: “Deploying OPNsense taught me how to configure VLAN tagging and firewall rules to segment lab traffic.”)*

---

## 🔑 Key Features
- **Virtualization & Orchestration** → Multi-node VM and container management via Proxmox  
- **Network Security** → VLAN segmentation, firewalling, VPN access  
- **Monitoring & Observability** → Centralized metrics and logs (Zabbix, log monitoring)  
- **Backup & Storage** → Disaster recovery with PBS and ZFS snapshots  
- **Automation** → Infrastructure-as-Code with Ansible/Terraform

📷 *Add screenshots of monitoring dashboards (Zabbix/Grafana) or PBS backup jobs here.*  
Example:  
`![Zabbix Dashboard](images/zabbix.png)`  
`![Proxmox Backup Server](images/pbs.png)`

---

## 🛠️ Skills Gained
- Virtualization & containerization (Proxmox, Docker, LXC)  
- Linux administration & self-hosted services  
- Network engineering (VLANs, OPNsense firewall, VPN)  
- Storage & backup management (TrueNAS, ZFS, PBS)  
- Infrastructure automation (Ansible, Terraform)

👉 *(Here you can add a closing paragraph: “This project demonstrates my ability to design and manage complex infrastructure similar to enterprise environments.”)*

---
