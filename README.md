# 🚀 Mini VPS Panel

A lightweight web-based VPS-like panel for managing Python, Node.js, and Shell scripts with user isolation and real-time monitoring.

## 📋 Table of Contents
- [Features](#-features)
- [Demo Credentials](#-demo-credentials)
- [Deployment](#-deployment)
- [Local Development](#-local-development)
- [Project Structure](#-project-structure)
- [Security Notes](#-security-notes)
- [Tech Stack](#-tech-stack)
- [Screenshots](#-screenshots)

## ✨ Features

### 🔐 Owner Dashboard
- Create/delete users with custom expiry times
- Generate shareable auto-login links
- Monitor all active user sessions
- Extend user expiry periods
- Auto-cleanup of expired users and their processes

### 👤 User Dashboard
- **File Management**: Upload multiple files (up to 200MB total)
- **Process Control**: Start/Stop/Restart `.py`, `.js`, `.sh` scripts
- **Package Management**: Install Python packages (`pip install`) or Node modules (`npm install`)
- **Real-time Logs**: Live log streaming with auto-refresh
- **File Operations**: View and delete uploaded files

## 🔑 Demo Credentials

| Role | Username | Password |
|------|----------|----------|
| Owner | `mrshuvo` | `mrshuvo` |

> ⚠️ **Important**: Change these credentials immediately after first login!

## 🚀 Deployment

### Deploy on Railway (Recommended)

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/yourusername/vps-panel.git
   git push -u origin main
