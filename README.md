# Welcome 

### Cybersecurity | Network Security

> **Detect. Investigate. Respond. Harden.**

I am a cybersecurity-focused IT professional building practical experience across **Security Operations, endpoint security, digital forensics, threat detection, network security, and security automation**.

My approach is strongly hands-on: build the lab, generate the telemetry, investigate the evidence, understand the attack path, and then develop a practical detection or response mechanism.

---

## 🛡️ Security Focus

```text
Security Operations        ███████████████████░░
Endpoint Security          ██████████████████░░░
Network Security           ██████████████████░░░
Digital Forensics          ████████████████░░░░
Threat Detection           ██████████████████░░░
Security Automation        ███████████████░░░░░
Python / Scripting         ██████████████░░░░░░
```

### Areas I Work With

* 🔎 Security Monitoring & Detection
* 🛡️ SOC / Blue-Team Operations
* 🖥️ Windows Endpoint Security
* 🧪 Malware & IOC Analysis
* 🧠 Memory Forensics
* 🌐 Network Security & Traffic Analysis
* 🚨 Incident Detection & Response
* 🔐 PowerShell Security
* 🧬 YARA-based Detection
* 📊 SIEM / Security Telemetry
* ⚙️ Security Automation
* 🧰 Vulnerability & Security Testing

---

# 🧰 Security Toolkit

### Security Operations

`Wazuh` `SIEM` `EDR` `Active Response` `Detection Engineering`

### Digital Forensics

`Volatility 3` `Memory Analysis` `Windows Forensics` `IOC Analysis`

### Detection Engineering

`YARA` `Sigma` `Windows Event Logs` `PowerShell Logging` `MITRE ATT&CK`

### Network Security

`Wireshark` `IPsec` `IKE` `ESP` `TCP/IP` `Firewall Analysis`

### Operating Systems

`Windows Server` `Windows` `Linux` `Ubuntu`

### Programming & Automation

`Python` `PowerShell` `Bash` `Git`

---

# 🔬 Featured Security Projects

## 01 — Wazuh SOC / Endpoint Security Lab

A practical security laboratory focused on endpoint monitoring, detection engineering and automated response.

### Work includes

* Windows endpoint monitoring
* PowerShell event detection
* File Integrity Monitoring
* Active Response
* Suspicious process detection
* Brute-force detection
* IOC monitoring
* YARA integration
* Endpoint investigation
* MITRE ATT&CK mapping

**Security workflow**

```text
Endpoint
   │
   ▼
Windows Telemetry
   │
   ▼
Wazuh Agent
   │
   ▼
Wazuh Manager
   │
   ├── Detection
   │
   ├── Correlation
   │
   └── Alert
          │
          ▼
     Investigation
          │
          ▼
     Response / Containment
```

---

## 02 — Windows Threat Detection

Research and laboratory work around detecting suspicious Windows activity.

Areas include:

* PowerShell execution
* Windows Event Logs
* Event ID 4104
* Suspicious command execution
* Script-block logging
* Process investigation
* Endpoint telemetry
* Application behavior

Example detection concept:

```text
PowerShell
    ↓
Script Block Logging
    ↓
Windows Event Log
    ↓
Wazuh Agent
    ↓
Detection Rule
    ↓
Alert
    ↓
Investigation
```

---

## 03 — Digital Forensics & Memory Analysis

Practical investigation using memory dumps and forensic tooling.

### Tools

* Volatility 3
* Windows memory analysis
* Process investigation
* Network connection analysis
* VAD / memory inspection
* Process trees
* Command-line analysis
* IOC extraction

Typical investigation workflow:

```text
Memory Image
     │
     ▼
OS Identification
     │
     ▼
Process Enumeration
     │
     ├── pstree
     ├── cmdline
     └── malfind
     │
     ▼
Network Analysis
     │
     ▼
IOC Extraction
     │
     ▼
Timeline / Evidence Correlation
```

---

## 04 — Malware & IOC Investigation

Security research involving suspicious documents, processes, network indicators and malicious artifacts.

Techniques include:

* IOC extraction
* YARA scanning
* Suspicious document analysis
* Process analysis
* Network IOC investigation
* PowerShell analysis
* Windows artifact investigation
* VirusTotal-based enrichment

---

## 05 — Network Security Laboratory

Hands-on network-security research involving:

* IPsec
* IKE
* ESP
* Firewall traffic
* NAT considerations
* Packet captures
* Wireshark
* Network troubleshooting
* VPN troubleshooting

Investigation methodology:

```text
Packet Capture
      ↓
Protocol Identification
      ↓
Handshake Analysis
      ↓
Endpoint Verification
      ↓
Directionality Analysis
      ↓
Firewall / NAT Investigation
      ↓
Root Cause
```

---

# 🎯 Current Learning Path

```text
                    CYBERSECURITY
                         │
        ┌────────────────┼────────────────┐
        │                │                │
       SOC              DFIR           NETWORK
        │                │                │
    Detection        Volatility       Wireshark
    Wazuh            Memory           IPsec
    SIEM             Malware          Firewall
        │                │                │
        └────────────────┼────────────────┘
                         │
                  SECURITY AUTOMATION
                         │
                    Python / PS
```

---

# 📚 Security Methodology

I try to approach security problems using a repeatable workflow:

### 01 — Observe

Collect telemetry and evidence.

### 02 — Detect

Identify suspicious behavior using rules, indicators and behavioral signals.

### 03 — Investigate

Correlate:

```text
Process
  +
User
  +
Command
  +
File
  +
Network
  +
Timestamp
```

### 04 — Respond

Contain or mitigate the activity where appropriate.

### 05 — Improve

Turn the investigation into:

* a detection rule
* a playbook
* an IOC
* a YARA rule
* a monitoring improvement
* a hardening measure

---

# 🧪 Security Lab Philosophy

I prefer building realistic laboratories instead of only studying individual tools.

A typical laboratory looks like:

```text
                    ┌───────────────┐
                    │   ATTACKER    │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │   NETWORK     │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ WINDOWS HOST  │
                    │               │
                    │ PowerShell    │
                    │ Processes     │
                    │ Files         │
                    │ Event Logs    │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ WAZUH AGENT   │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ WAZUH MANAGER │
                    └───────┬───────┘
                            │
                 ┌──────────┴──────────┐
                 ▼                     ▼
             DETECTION             RESPONSE
                 │                     │
                 └──────────┬──────────┘
                            ▼
                      INVESTIGATION
```

---

# 🗂️ Repository Structure

| Directory     | Purpose                         |
| ------------- | ------------------------------- |
| `/labs`       | Practical security laboratories |
| `/writeups`   | Investigation and CTF writeups  |
| `/detections` | Detection rules and logic       |
| `/scripts`    | Security automation             |
| `/yara`       | YARA rules                      |
| `/forensics`  | DFIR resources                  |
| `/network`    | Network-security research       |

---

# 🧠 Security Principles

```text
Visibility
    ↓
Detection
    ↓
Investigation
    ↓
Containment
    ↓
Recovery
    ↓
Hardening
    ↓
Continuous Improvement
```

Security is not only about identifying an attack.

It is about understanding **what happened, why it happened, what evidence remains, how to contain it, and how to detect it next time.**

---

# 📈 GitHub Activity

<!-- Replace these with your preferred GitHub statistics services if desired. -->

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME\&show_icons=true\&hide_border=true\&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME\&layout=compact\&hide_border=true)

---

# 📫 Contact

* LinkedIn: ` `

---

## ⚠️ Security Research Disclaimer

All security testing, malware analysis, exploitation research and laboratory activities documented here are intended for **authorized environments, educational purposes and defensive security research**.

Do not use these techniques against systems without appropriate authorization.

---

> **Build the lab. Generate the evidence. Find the signal. Understand the attack. Improve the defense.**
