# IT-Portfolo
# Enterprise IT Help Desk & Remote Support Portfolio

Welcome to my IT Support portfolio. This repository showcases real-world technical troubleshooting workflows, incident lifecycle management, and multi-campus network diagnostics based on enterprise standards.

## 🛠️ Core Technical Skills
* **Help Desk Ticketing Systems:** Remedy (BMC Helix) Incident Management
* **Operating Systems:** Windows 10/11 Enterprise, OS Deployment & Image Recovery
* **Networking:** TCP/IP Stack, DNS, DHCP, LAN Connectivity, Switch Port Diagnostics
* **Command-Line Tools:** `ipconfig`, `ping`, `traceroute`, `nslookup`

---

## 📋 Featured Projects & Workflow Simulations

### 1. Remote IT Support & Lifecycle Management (DeVry University Simulation)
* **Scenario:** A remote user at a regional Virginia campus location experienced a persistent boot loop due to a corrupted system update, breaching standard operations.
* **Triage & Resolution:** Logged and prioritized the ticket in Remedy. Remotely isolated the BCD corruption and guided the user through an authenticated network boot environment to successfully deploy a clean, DeVry-validated system recovery image. 
* **Remedy Closure Entry:** 
  > `"Status: Closed. Root Cause: OS/Software corruption post-update. Resolution: Initiated secure network boot, successfully deployed DeVry-validated recovery image, and repaired BCD integrity. Verified remote domain connectivity. Completed within 45-minute SLA milestone."`

### 2. Enterprise Network Diagnostics & Support Simulation
* **Scenario:** A campus staff member lost access to the local intranet and student registration databases, disrupting administrative workflows.
* **Triage & Resolution:** Utilized command-line utilities (`ipconfig /all`) to diagnose an invalid APIPA address (169.254.x.x). Coordinated a localized switch port reset and executed an IP release/renew to bind the client device to a valid dynamic campus subnet.
* **Remedy Closure Entry:**
  > `"Status: Closed. Root Cause: Failed DHCP lease due to localized switch port drop. Resolution: Confirmed NIC functionality via loopback, performed IP release/renew, and bound device to valid campus subnet. Verified database access. SLA met."`

---

## 🌐 Live Website
You can view the full, interactive layout of this portfolio live on the web:
👉 **[View My Live Portfolio Site](https://victor-donald.github.io/IT-Portfolo/)**
