# 🌍 TravelMemory – AWS EC2 Deployment

## 📌 Project Overview

This project demonstrates deployment of the **TravelMemory MERN Stack Application** on an AWS EC2 instance.

The application allows users to store and manage travel memories with images and details.

---

## 🧰 Tech Stack

- Frontend: React
- Backend: Node.js + Express
- Database: MongoDB Atlas
- Web Server: Nginx
- Hosting: AWS EC2
- Process Manager: PM2

---

## 🏗️ Architecture Diagram

![Architecture Diagram](architecture.png)

---

## 🚀 Deployment Steps

### 1. Launch EC2 Instance
- Created Ubuntu EC2 instance on AWS
- Configured security group:
  - Port 22 (SSH)
  - Port 80 (HTTP)

---

### 2. Connect to EC2
```bash
ssh -i your-key.pem ubuntu@<EC2_PUBLIC_IP>
