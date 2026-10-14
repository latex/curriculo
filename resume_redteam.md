# Leandro de Araújo Teixeira

**Staff / Senior Red Team Operator & Adversary Emulation Specialist**  
**Offensive Security, Exploit Development, Firmware & Linux Kernel Driver Reverse Engineering**  
São Paulo, SP – Brazil (Open to Remote Worldwide)  
📞 +55 (11) 93001-8609 | ✉️ [leandro.tex@outlook.com](mailto:leandro.tex@outlook.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/leandrotex/) | 💻 [GitHub (latex)](https://github.com/latex)

---

## 🎯 Executive Summary

Senior Offensive Security Specialist, Red Team Operator, and Reverse Engineer with over three decades of deep technical trajectory across the computing landscape. Demonstrates proven excellence spanning high-level enterprise environments—multi-cloud infrastructures (GCP, Azure), Kubernetes clusters, microservices, and AI/LLM systems—down to the bare-metal core: **embedded firmware reverse engineering**, binary disassembly (ELF/PE), and **Linux kernel device driver reverse engineering and development in C**.

Proven track record executing end-to-end adversary emulation campaigns aligned with MITRE ATT&CK, engineering evasive Command-and-Control (C2) tooling and custom payloads (Python, Go, C, Rust, Bash), bypassing modern EDRs and WAFs, and executing complex lateral movement across hybrid enterprises. Pioneer in **AI Red Teaming**, proactively stress-testing enterprise generative AI architectures (GCP Vertex AI / Gemini) against Prompt Injection, Jailbreaking, guardrail circumvention, and RAG data exfiltration.

Co-founder of **Garoa Hacker Clube** (Brazil's premier hackerspace) and **Fundação HackerSpace**, pairing authentic hacker curiosity and deep low-level research with the executive ability to translate complex adversary simulations into high-impact remediation strategies and Purple Team collaborations.

---

## 🛠️ Technical Arsenal & Core Competencies

- **Adversary Emulation & Red Team Operations:** APT Simulation (MITRE ATT&CK), End-to-end Offensive Campaigns (Initial Access $\to$ Privilege Escalation $\to$ Lateral Movement $\to$ Exfiltration), EDR/AV Evasion, Obfuscation, C2 Infrastructure & Payloads (Cobalt Strike, Sliver, Havoc, Empire, Custom C2s).
- **Firmware Reverse Engineering & Hardware Hacking:** Physical flash memory dumping (SPI, NAND, EEPROM) via hardware debugging interfaces (JTAG, UART, I2C, SPI, Bus Pirate, Logic Analyzers), firmware unpacking (SquashFS, CramFS, JFFS2 via Binwalk), uncovering embedded 0-days, hardcoded credentials, buffer overflows, and proprietary communication protocol analysis.
- **Linux Kernel & Device Driver Reverse Engineering:** Kernel module development and reverse engineering (C), kernel debugging (GDB, KDB/KGDB, QEMU, tracepoints, eBPF), bus traffic dissection (USB, PCI, I2C), reverse engineering proprietary binary blobs to build native open-source Linux drivers.
- **Binary Disassembly & Exploit Development:** Ghidra, IDA Pro, Radare2/Cutter, GDB with GEF/Pwndbg, x64dbg, Binwalk, Pwntools, static and dynamic analysis of x86/x64, ARM, and MIPS binaries, defeating modern exploit mitigations (DEP/NX, ASLR, Stack Canaries).
- **AI Red Teaming & LLM Security:** Direct & Indirect Prompt Injection, Advanced Jailbreaking, Prompt & Context Leakage, Guardrail Evasion, Training Data Poisoning, and OWASP Top 10 for LLMs/GenAI validation on enterprise models (GCP Vertex AI, Model Garden, Agentic Workflows).
- **Cloud & Network Penetration Testing:** Google Cloud Platform (GCP), Microsoft Azure, AWS, Kubernetes Security & Container Breakout (GKE/AKS), Active Directory / Entra ID attack paths (BloodHound, Mimikatz, Impacket, CrackMapExec), Burp Suite Professional, REST & GraphQL API Security.
- **Offensive Tooling & Automation:** C, Rust, Python, Go, Bash, PowerShell, x86/ARM Assembly, payload automation, and custom exploit integration.

---

## 💼 Professional Experience

### **Jeitto (Fintech / Digital Credit & Payments)** | *Oct 2024 – Oct 2026 (2 years)*  
**Staff / Senior Offensive Security Engineer & Red Team Lead**
- **Adversary Emulation Campaigns:** Designed and executed threat-informed adversary simulations (MITRE ATT&CK) against high-throughput payment processing backends, digital credit engines, and card rails on GCP and Azure.
- **C2 Tooling & EDR Evasion:** Developed custom in-memory payloads and modular C2 architectures that bypassed commercial WAF rules (Google Cloud Armor) and enterprise EDR agents, identifying critical detection blind spots before malicious actors could exploit them.
- **Enterprise AI Red Teaming:** Led offensive operations against LLM-powered financial customer and internal agent services hosted on GCP Vertex AI, successfully executing prompt injections and guardrail bypasses to extract simulated PII, directly informing the implementation of hardened AI defenses.
- **Offensive API Security:** Discovered and exploited Broken Object Level Authorization (BOLA/IDOR) and business logic flaws in transactional microservices, preventing multi-million dollar fraud vectors.
- **Purple Team Enablement:** Facilitated post-operation debriefs with Blue Team and SOC analysts, converting offensive telemetry into custom SIEM detection rules and increasing overall detection coverage by 88%.

---

### **Clinicorp (Healthtech / Dental SaaS & Financial Management)** | *Oct 2022 – Sep 2024 (2 years)*  
**Senior Red Team Specialist & Penetration Tester**
- **Data Exfiltration Simulation:** Spearheaded black-box adversary campaigns targeting electronic health records (EHR) and financial payment flows, assessing compliance posture under LGPD, HIPAA, and industry privacy mandates.
- **Identity & Privilege Escalation:** Mapped and exploited attack paths across hybrid identity infrastructures (IAM / SSO / Entra ID), leveraging over-permissioned service accounts and exposed secrets on GCP and Azure to achieve tenant-wide administration.
- **Web & Mobile Pentesting:** Conducted deep penetration tests across React web platforms and iOS/Android mobile apps, identifying authentication bypasses, insecure cryptographic implementations, and client-side data tampering.
- **Container Breakout & CI/CD Auditing:** Simulated container escape attacks within Kubernetes (GKE) clusters and poisoned development pipelines to demonstrate supply-chain risks, eliminating 92% of critical vulnerabilities prior to production release.

---

### **Locaweb SA (Cloud & Hosting Infrastructure)** | *May 2019 – Sep 2022 (3 years 5 months)*  
**Senior Offensive Security Engineer / Threat Emulation**
- **Large-Scale Infrastructure Red Teaming:** Conducted adversary emulation operations across massive multi-tenant data centers, bare-metal clusters, and private/public cloud environments serving hundreds of thousands of businesses.
- **Active Directory Exploitation:** Utilized BloodHound to analyze complex multi-domain Active Directory forests, discovering hidden privilege escalation paths to Domain Admin and root hypervisor management interfaces.
- **Hypervisor & Network Segmentation Audits:** Assessed isolation boundaries in virtualization stacks (KVM, OpenStack) and internal enterprise networks, exploiting misconfigured VLANs and perimeter firewalls.
- **Reverse Engineering Legacy Systems:** Disassembled and audited closed-source, compiled internal infrastructure services using Ghidra and Radare2, identifying memory corruption vulnerabilities and insecure system calls.

---

### **PagSeguro SA (Digital Banking & Merchant Services)** | *May 2017 – Apr 2019 (2 years)*  
**Offensive Security Engineer & DevOps Security**
- Performed penetration tests and red team simulations against payment gateways, transparent checkouts, and SmartPOS hardware devices.
- Tested physical payment terminal security, evaluating locked-down Android bootloaders, exposed debug interfaces (UART/ADB), and resistance to firmware tampering.
- Engineered automated exploit proofs-of-concept (PoCs) to demonstrate the risk of privilege escalation across AWS infrastructure and CI/CD pipelines.

---

### **TCIBPO LTDA** | *May 2016 – Apr 2017 (1 year)*  
**Penetration Tester & Security Automation Engineer**
- Conducted infrastructure and network penetration testing across enterprise client environments hosted on AWS and Azure.
- Built Python and Bash automation tools to scale port scanning, service fingerprinting, and configuration vulnerability auditing.

---

### **HCFMUSP (Hospital das Clínicas – University of São Paulo)** | *Jan 2014 – Apr 2016 (2 years 4 months)*  
**Senior Security Analyst & Researcher (R&D)**
- Conducted offensive security evaluations and protocol analysis on Internet of Medical Things (IoMT) connected devices and hospital management systems.
- Identified unencrypted proprietary communication protocols, weak authentication handshakes, and lateral movement vectors across critical clinical networks.

---

### **Conectiva Linux** | *Systems Analyst / Kernel & Driver Researcher*  
**Hardware & Firmware Reverse Engineering, Linux Kernel Driver Development**
- **Kernel Device Driver Engineering:** Developed, modified, and ported Linux kernel device drivers in C. Reverse-engineered hardware chipsets lacking public documentation or native Linux support by capturing and dissecting bus traffic and decompiling proprietary vendor driver binaries.
- **ELF Binary Analysis & Kernel Internals:** Conducted in-depth research on Linux kernel data structures, system call hooks, secure packaging, and system-level hardening.

---

## 🔬 Firmware & Low-Level Hardware Reverse Engineering (Practical Highlights)

- **Physical & Logical Firmware Acquisition:** Direct chip-off and in-circuit memory dumping (SPI/I2C flash) using SOIC test clips, Bus Pirate, Raspberry Pi, and hardware programmers.
- **Firmware Triage & Unpacking:** Reconstructing filesystem hierarchies from raw, opaque binary images using Binwalk, extracting SquashFS/CramFS/JFFS2 partitions, and analyzing U-Boot and secondary bootloader headers.
- **Embedded Vulnerability Hunting:** Reverse-engineering compiled ARM and MIPS firmware binaries in **Ghidra, IDA Pro, and Radare2** to uncover hardcoded backdoor credentials, insecure debug routines, and memory corruption bugs.
- **Custom Open-Source Linux Drivers:** Real-world track record creating open-source Linux kernel drivers for proprietary devices (e.g., `canvasbio-cb2000-linux-driver`), reverse-engineering USB protocols from scratch to achieve full native hardware functionality.

---

## 🎓 Education

- **B.S. in Computer Engineering** – Universidade Presbiteriana Mackenzie
- **Postgraduate Specialization in Data Science** – Johns Hopkins University *(In progress)*
- **Associate Degree in Mechatronics** – SENAI-SP *(Rigorous training in electronics, microcontrollers, digital circuits, and communication buses)*

---

## 📜 Certifications & Specialized Training

- **Offensive & Red Team:** Methodology aligned with OSCP / CRTO, Advanced Network Penetration Testing, Defense Evasion & Exploit Techniques.
- **Cloud & Architecture:** Google Cloud Platform (GCP) Security & Architecture, Microsoft Azure Security Technologies.
- **Linux & Kernel:** Linux Conectiva Certified, LPIC-1, LPIC-2, UTHA Linux Center (Cryptography, Firewalls & Advanced Security).
- **Networking:** Cisco / Cyclades (Routing, Switching & Network Administration).

---

## 🌐 Community Leadership, Hacker Culture & Keynotes

- **Garoa Hacker Clube:** Founding member of Brazil’s first and most influential hackerspace, leading hands-on workshops in hardware hacking, reverse engineering, offensive security, and open-source software.
- **Fundação HackerSpace:** Co-Founder and advocate for collaborative technical education (2008 – Present), driving free open-source software, digital inclusion, and hardware security research.
- **Campus Party Brazil:** Official Keynote Speaker across multiple editions (2010, 2012, 2013, and CP 10), delivering talks and live demos on Linux kernel exploitation, network security, and offensive tradecraft.
- **Gentoo Linux User Group SP:** Former President, organizing technical meetups focused on source-based operating system compilation, low-level optimization, and kernel security.
- **Hackathon Mentor:** Technical mentor across 20+ national hackathons, coaching teams on secure API design, cloud architecture, and resilient system engineering.
