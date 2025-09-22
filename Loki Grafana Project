# 📊 Centralized Log Monitoring with Grafana Loki + Promtail

## 📌 Overview
This project sets up a **centralized logging solution** for my homelab using **Grafana Loki**, **Promtail**, and **Grafana dashboards**.  

Logs from Proxmox, Vaultwarden, and other containers are aggregated into a single system, making it easy to **search, visualize, and troubleshoot** across the entire environment.

---

## 🛠️ Tech Stack
- **Loki** – log database optimized for efficiency and scale  
- **Promtail** – log collection agent installed on Proxmox and select VMs/containers  
- **Grafana** – dashboards and visualization for log analysis  
- **Proxmox LXC Container** – hosts the Loki stack using Docker Compose  

---

## ⚙️ Architecture
- Promtail agents run on multiple nodes (Proxmox host + Vaultwarden VM)  
- Logs are forwarded to Loki running in a containerized environment  
- Grafana connects to Loki as a data source for visualization  
- Dashboards display real-time logs for troubleshooting and monitoring  

📷 *Insert diagram here — e.g., Proxmox → Promtail → Loki → Grafana*  

Example:  
`![Log Monitoring Architecture](images/Loki_Architecture.png)`

---

## 🚀 Deployment
1. Provisioned an **LXC container** in Proxmox running Docker  
2. Deployed the **Loki stack** (`docker-compose.yml`) with Loki, Promtail, and Grafana  
3. Configured Promtail on:  
   - Proxmox host (system logs)  
   - Vaultwarden container (application logs)  
   - Other homelab services as needed  
4. Built Grafana dashboards to track error logs, warnings, and service activity  

📷 *Add screenshot of your Grafana dashboard here*  
Example:  
`![Grafana Logs Dashboard](images/Loki-Grafana-Dashboard.png)`

---

## 📈 Outcomes
- **Single-pane-of-glass** monitoring for logs across multiple services  
- Improved troubleshooting → search across all logs instead of SSH-ing into each VM  
- Learned log parsing, pipeline stages, and how to visualize trends in Grafana  

---

## 💡 Key Learnings
- How **Promtail labels and filters logs** before sending them to Loki  
- Connecting Loki as a **Grafana data source**  
- Designing **effective Grafana dashboards** for monitoring and troubleshooting  

---
