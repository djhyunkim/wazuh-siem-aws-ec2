# 🛠️ Wazuh SIEM Setup Guide on AWS EC2

This guide walks through deploying and configuring a basic Wazuh SIEM on an AWS EC2 instance running Ubuntu Server.

---

## Prerequisites

- AWS account
- Basic knowledge of Linux and SSH
- An EC2 instance (Ubuntu 20.04 or later)
- Security Group with these ports open:
  - `22` (SSH)
  - `443` (Wazuh Web UI)
  - `55000` (Wazuh Agent Registration — optional)
  - `1514` (TCP/UDP for log forwarding — optional)

---

## Step 1: Launch an EC2 Instance

1. Go to [AWS EC2](https://console.aws.amazon.com/ec2/)
2. Click **Launch Instance**
3. Choose **Ubuntu Server 20.04 LTS**
4. Instance type: `t2.medium` or higher (recommended for Wazuh)
5. Create or select a key pair
6. Under **Network Settings**:
   - Edit **Inbound Rules**
     - Allow SSH (port 22)
     - Allow HTTPS (port 443)
7. Launch the instance

---

## Step 2: Connect via SSH

From your local terminal:

```bash
ssh -i /path/to/your-key.pem ubuntu@<your-ec2-public-ip>
