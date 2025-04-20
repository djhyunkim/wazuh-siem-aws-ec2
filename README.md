# Wazuh SIEM on AWS EC2
Setup and configuration of a Wazuh SIEM system on AWS EC2

This project documents the installation and configuration of the Wazuh SIEM platform on an AWS EC2 instance. 
It focuses on building a foundational monitoring and log analysis environment using open-source tools in the cloud.

# Project Goals
- Deploy and configure Wazuh SIEM on AWS EC2
- Enable host-based intrusion detection and real-time log monitoring
- Learn basic cloud setup and security group configurations
- Practice managing a SIEM environment in a virtualized lab setting

# Tools & Technologies
- AWS EC2 (Ubuntu or Debian)
- Wazuh (Manager, API, and Web Interface)
- OpenSSH
- ufw (firewall)
- systemctl / journald

# Screenshots
See the `screenshots/` folder for images of the deployment process and working Wazuh interface.

# Setup Guide
The step-by-step installation instructions are available in [`setup-guide.md`](setup-guide.md). It includes:
- EC2 instance provisioning
- Wazuh installation (via script or manual steps)
- Opening required ports and configuring security groups
- Accessing the Wazuh dashboard

# Outcomes
- Successfully deployed a functioning SIEM system
- Monitored and collected logs from the host system
- Learned how to manage a basic cloud-based detection environment

# Lessons Learned
- Importance of properly configuring firewall rules (ufw, EC2 security groups)
- How Wazuh manages agents, logs, and alerts
- Gained hands-on experience with Linux server administration and cloud services

# Documentation
- [Setup Guide](setup-guide.md)
- [Troubleshooting Common Issues](docs/troubleshooting.md)

