# 🧠 n8n-deploy

A simple Docker-based setup to deploy your **n8n automation workflows** anywhere — locally or on cloud providers like **Koyeb**, **Railway**, or **Fly.io**.

---

## 📦 What is n8n?

[n8n](https://n8n.io/) is a powerful workflow automation tool — similar to Zapier or Make — but **self-hosted**, **free**, and **privacy-friendly**.  
You can connect APIs, automate tasks, and build logic visually without coding.

---

## 🚀 Quick Start (Local Setup)

### Prerequisites
- Node.js **v18+** *(if running via npm)* OR
- Docker installed on your machine

### Run with Docker
```bash
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n:latest
```
Then open http://localhost:5678

→ Log in with the credentials you’ll set via environment variables.
