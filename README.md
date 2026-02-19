# Enterprise Linux SOC Lab

# Overview
This project documents a multi-server Ubuntu 24.04 homelab built in VirtualBox to simulate a small enterprise environment including a production server, attacker node, and security operations (SOC) monitoring server.The purpose of this lab is to develop practical Linux administration, networking, and security monitoring skills through real deployment and troubleshooting not just theory.

# Lab Architecture

# Virtualisation
- Platform: Oracle VirtualBox
- Network Segmentation:
  - NAT adapter (internet access)
  - Internal network (server-to-server communication)

# Servers

# 1. UBU-SRV (Production Server)
- Ubuntu Server 24.04 LTS
- Terminal-only environment
- OpenSSH installed and configured
- System services managed via systemd

# 2. UBU-ATK (Attacker Node)
- Used to simulate internal attack scenarios
- Network reconnaissance and brute-force testing
- Used to generate logs for detection testing

# 3. UBU-SOC (Security Operations Server)
- Elastic Stack deployment
- Central log ingestion
- Monitoring and analysis

# Skills Demonstrated
- Ubuntu Server installation and configuration
- SSH deployment and management
- systemctl service control and troubleshooting
- VirtualBox networking configuration
- NAT vs internal networking concepts
- Troubleshooting host-only adapter conflicts
- Understanding of attack simulation and log generation
- Exposure to SIEM architecture concepts

# Problems Encountered & Resolved
- Host-only adapter failure due to Windows security interference
- VirtualBox driver conflicts
- SSH appearing inactive due to socket activation
- CD-ROM ISO unmount errors
- Networking isolation issues

Each issue required structured troubleshooting and environment-level problem solving.

# Future Expansion

- Integration with Windows Active Directory lab
- Centralised log forwarding from Windows to Elastic
- Simulated attack detection workflows
- Network segmentation refinement
- Alert rule development

# Author
Jacob Sibbald  
Building enterprise-style infrastructure and detection labs for professional development.
