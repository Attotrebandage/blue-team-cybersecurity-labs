# Blue Team Cybersecurity Labs

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,100:00B4DB&height=220&section=header&text=Blue%20Team%20Cybersecurity%20Labs&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Defend%20Analyze%20And%20Harden%20Your%20Infrastructure&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-3.1.0-00B4DB?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-93.2K-0F2027?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FF5252?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Platform](https://img.shields.io/badge/platform-linux%20%7C%20windows%20%7C%20docker-4CAF50?style=for-the-badge&logo=linux&logoColor=white)

</div>

---

## 🛡️ Master The Art Of Digital Defense

While the offensive side of cybersecurity (Red Teaming) often gets the spotlight, the true heroes of the digital world are the defenders. **Blue Team Cybersecurity Labs** is a comprehensive, hands-on training repository designed to equip security analysts, SOC operators, and incident responders with the practical skills needed to protect modern infrastructure.

This repository provides a series of realistic, containerized lab environments. Each lab simulates a specific threat scenario: from a compromised web server to a ransomware outbreak. Your mission is to investigate the logs, analyze the network traffic, identify the root cause, and apply the correct remediation steps.

Unlike theoretical courses, these labs are entirely practical. You will be working with real tools like Wireshark, Splunk, YARA, and Sysmon. Each lab includes a detailed briefing, the necessary environment files, and a walkthrough guide for instructors. It is the perfect sandbox for anyone preparing for certifications like CompTIA CySA+, GCIH, or just looking to build real-world defensive skills.

<img width="1251" height="765" alt="dashboard (1)" src="https://github.com/user-attachments/assets/ba0cc2e7-210e-4ac7-af40-d1f7ffa5bbe3" />


---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🕵️ **Incident Response** | Investigate simulated breaches and write post-mortem reports |
| 📊 **Log Analysis** | Parse and analyze Sysmon, Windows Event, and Apache logs |
| 🌐 **Network Forensics** | Use Wireshark and Zeek to hunt for C2 traffic and exfiltration |
| 🛡️ **Hardening Guides** | Step-by-step labs on securing Linux, Windows, and Active Directory |
| 🧪 **Malware Analysis** | Safe, static analysis of real-world malware samples |
| 🐳 **Docker Based** | Instantly spin up a lab environment with a single command |
| 📖 **Detailed Walkthroughs** | Instructor guides with the exact commands to find the answers |
| 🎯 **MITRE ATT&CK Mapping** | Every lab is mapped to real-world adversary techniques |

---

## 🚀 Quick Setup

To run the labs, you will need Docker, Docker Compose, and at least 8GB of RAM. The labs are designed to be fully isolated from your host machine.

```bash
# Clone the repository
git clone https://github.com/your-username/blue-team-cybersecurity-labs.git

# Navigate into the directory
cd blue-team-cybersecurity-labs

# Start the first lab (e.g., Lab 01: Web Server Compromise)
cd labs/01-web-compromise
docker-compose up -d
```

Once the containers are running, you will find a `target/` folder in the lab directory. This folder contains the logs, network captures, and artifacts you need to analyze. Read the `BRIEFING.md` file first to understand the scenario. When you think you have found the answer, check the `WALKTHROUGH.md` file to verify your findings.

---

<div align="center">

### 🔗 Ready to start your Blue Team training?

[![Get Labs](https://img.shields.io/badge/🛡️_GET_LABS-0F2027?style=for-the-badge&logoColor=white)](https://share.google/j1dgDuXhzcqnLRIzt)

</div>

---

## 🧠 How The Labs Are Structured

Each lab in this repository follows a consistent, pedagogical structure designed to maximize learning retention. 

1. **The Briefing:** You are given a scenario. For example, "You are a SOC analyst. At 02:00 AM, an alert triggered on server WEB-01 indicating a possible reverse shell."
2. **The Artifacts:** You are provided with real artifacts. This could be a PCAP file, a memory dump, or a raw text log. These are generated in a controlled environment and contain real indicators of compromise (IOCs).
3. **The Investigation:** You must use your tools to investigate. You might need to use `grep` to search for specific IP addresses in the logs, or Wireshark to follow a TCP stream.
4. **The Analysis:** Once you find the evidence, you must answer the questions in the `QUESTIONS.md` file. What was the initial access vector? What data was exfiltrated?
5. **The Remediation:** Finally, you must propose a fix. How do you prevent this from happening again?

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-00B4DB?style=for-the-badge&logoColor=white)](https://share.google/j1dgDuXhzcqnLRIzt)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

Blue Team defense is a community effort. If you have designed a new lab, found a bug in a scenario, or want to contribute a new walkthrough, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-lab`).
3. **Commit** your changes (`git commit -m 'Add new ransomware lab'`).
4. **Push** to the branch (`git push origin feature/new-lab`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed guidelines on creating new labs and submitting artifacts. We also have an active Discord server where you can share your investigation notes, ask for help with tools, and discuss the latest threats in the wild.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@blueteam-labs.dev.

---

<div align="center">

### ⭐ If these labs help you level up your skills, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FF5252?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username/blue-team-cybersecurity-labs)

---

### 🚀 Start defending today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-4CAF50?style=for-the-badge&logoColor=white)](https://share.google/j1dgDuXhzcqnLRIzt)

<sub>Crafted with precision and ❤️ by the Blue Team Cybersecurity Labs community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:00B4DB,100:0F2027&height=120&section=footer)

</div>
