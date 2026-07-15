# 🖥️ System and Network Analysis

## Overview

This project demonstrates my hands-on exploration of Windows system processes and active network connections. The objective was to understand how an operating system manages background services and how applications communicate with external servers over the internet.

Through this exercise, I developed foundational skills in system observation, process identification, and basic network investigation—skills that are essential for Security Operations Center (SOC) analysts.

---

## Windows Process Analysis

### Objective
To identify and understand legitimate Windows background processes and their role in maintaining system functionality and security.

### Activities Performed
- Inspected running processes using Windows Task Manager.
- Identified and researched essential Windows processes, including:
  - **Service Host (svchost.exe)**
  - **Desktop Window Manager (dwm.exe)**
  - **Secure System**
- Distinguished between user applications and critical operating system processes.

### Key Learning
Understanding normal Windows processes is fundamental to identifying abnormal or malicious activity during security monitoring and incident investigations.

---

## Network Connections Analysis

### Objective
To analyze active network connections and identify the organizations behind external IP addresses communicating with the system.

### Activities Performed
- Monitored active network connections using the `netstat -an` command.
- Examined active **ESTABLISHED** connections.
- Performed IP ownership lookups for external connections.

### Findings
The analyzed IP addresses were registered to:
- **Google LLC**
- **Cloudflare**
- **Microsoft Corporation**

The observed connections were consistent with trusted services and normal operating system and application behavior.

### Key Learning
This exercise reinforced the importance of validating outbound network connections and understanding normal network behavior—an essential skill for identifying suspicious communication during security investigations.

---

## Tools & Technologies
- Windows Task Manager
- Command Prompt
- Netstat
- WHOIS / IP Lookup Tools

---

## Skills Demonstrated
- Windows Process Analysis
- Network Connection Monitoring
- IP Address Investigation
- Basic Threat Analysis
- Cybersecurity Fundamentals
- Analytical Thinking

---

## Evidence

Screenshots documenting the process analysis, network connections, and IP ownership verification are included in this directory.
