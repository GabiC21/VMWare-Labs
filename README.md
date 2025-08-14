# VMware NSX - Networking Fundamentals Lab Summary

This repository contains a walkthrough and command outputs from the **VMware NSX Networking Fundamentals Hands-on Lab (HOL-2540-01-VCF-L)**.

# VMware NSX Networking Fundamentals – Lab Summary

![Network Topology](network_topology.png)

## Overview
This lab simulates a **VMware NSX** environment to explore core networking concepts, topology management, and troubleshooting workflows.  
It was completed in a hosted Windows-based lab environment with multiple virtual machines simulating different roles in a virtualized network.

The primary goal was to practice:
- Network connectivity verification
- IP routing inspection
- DNS testing
- Simulated troubleshooting of multi-node environments

---

## Lab Environment
The topology included:
- **ny-web-01a** – Web server node (New York)
- **ny-edge-01a** – Edge gateway node
- **sg-web-01a** – Web server node (Singapore)
- **NSX Manager** – Centralized network controller

---

## Steps Taken

### 1. Environment Access
- Logged into the hosted lab environment using provided credentials.
- Accessed **ny-web-01a** console from the lab control panel.

### 2. Basic Connectivity Tests
- Verified IP configuration:
  ```bash
  ip addr
---


---

*Author:* Gabi Conceicao  
*Date:* August 2025

