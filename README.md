# NGINX Domain Hosting Project

## Overview
This project demonstrates hosting a static website on an AWS EC2 instance using NGINX and connecting it to a custom domain.

---

## What I built

- Deployed EC2 instance on AWS
- Installed and configured NGINX
- Deployed custom HTML website
- Configured DNS A record for domain mapping
- Enabled public access over HTTP/HTTPS

---

## Deployment Flow

Domain → DNS (Cloudflare) → EC2 Public IP → NGINX → Website

---

## 🚀 CI/CD Pipeline (GitHub → EC2 Deployment)

This project uses a simple CI/CD pipeline to automatically deploy changes to an AWS EC2 server.

### 🔄 How it works

1. Code is pushed to the `main` branch on GitHub.
2. GitHub Actions workflow is triggered automatically.
3. The workflow connects to the EC2 instance using SSH.
4. Latest code is pulled from the GitHub repository on the server.
5. NGINX is reloaded to apply the new changes.
6. The updated website is live immediately.

### ⚙️ Tech Stack

- GitHub Actions (CI/CD automation)
- AWS EC2 (hosting server)
- NGINX (web server)
- SSH (secure deployment connection)

### 📦 Deployment Flow

GitHub Repository → GitHub Actions → SSH to EC2 → Pull Latest Code → Reload NGINX → Live Website

---

## Website

A static HTML page served using NGINX.

---

## Technologies Used

- AWS EC2
- NGINX
- Cloudflare DNS
- Linux (Amazon Linux 2023)
- HTML/CSS

---

## Result

The website is accessible via a custom domain and EC2 public IP.

---

## Evidence

See networking/screenshots
