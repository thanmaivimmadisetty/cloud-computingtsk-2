# ☁ Task 2 – Launch a Virtual Machine (VM) Instance

## 🎯 Objective
To understand how *cloud virtual machines* work by creating, configuring, and connecting to a *cloud-based server instance* using a free-tier cloud platform.  
This task gives hands-on learning of *Infrastructure-as-a-Service (IaaS)* — the base layer of cloud computing.

---

## 🛠 Tools (Free)
You may use *any one* of the following:
- *AWS EC2 Free Tier*

---

## 📌 Deliverables
Submit the following:

- ✅ Screenshot of *Running VM Instance* (cloud dashboard)
- ✅ Screenshot of *SSH terminal connection*
- ✅ A short note (2–3 lines) with your VM configuration  
  (Example: Ubuntu 22.04, e2-micro, asia-south1)

---

## 🧭 Step-by-Step Guide

### 1️⃣ Login & Setup
- Create an account on *Google Cloud* or *AWS*
- Activate *Free Tier / Trial Credits*

### 2️⃣ Create VM Instance
- Go to: *Compute Engine → VM Instances → Create Instance*
- OS: Ubuntu 22.04 LTS
- Machine Type: t3.micro (Free Tier)
- Region: nearest to you (for low latency)

### 3️⃣ Configure Firewall
Enable:
- ✅ *Allow HTTP traffic*
- ✅ *Allow HTTPS traffic*

### 4️⃣ Launch VM
- Click *Create*
- Wait until status shows *Running*
- Note your *External IP*

### 5️⃣ Connect via SSH
- Click *SSH → Open in Browser*
- A terminal window opens — this is your *remote Linux VM*

### 6️⃣ Test Commands
Run:

```bash
uname -a
ls
whoami
