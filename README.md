<h1 align="center">Hi, I'm Julio 👋</h1>
<h3 align="center">Computer Information Technology Student @ BCIT · Aspiring Cybersecurity Analyst</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2EA44F&center=true&vCenter=true&width=600&lines=Aspiring+Cybersecurity+Analyst;Network+Defense+%26+Secure+Systems;Wazuh+%C2%B7+Linux+%C2%B7+AWS;Always+learning+something+new" alt="Typing SVG">
</p>

<p align="center">
  <a href="mailto:santosrosajulio@gmail.com"><img src="https://img.shields.io/badge/Email-santosrosajulio%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Location-Richmond%2C%20BC-0d1117?style=flat-square&logo=googlemaps&logoColor=white" alt="Location">
  <img src="https://img.shields.io/badge/Status-Open%20to%20Entry--Level%20IT%20Roles-2ea44f?style=flat-square" alt="Open to opportunities">
</p>

---

```bash
julio@bcit:~$ whoami
> CIT student at BCIT with hands-on experience across the IT stack:
> programming, databases, networking, systems, and the command line.

julio@bcit:~$ cat focus.txt
> Cybersecurity: network defense, secure systems, and threat analysis.

julio@bcit:~$ echo $GOAL
> Build secure, reliable systems and help organizations stay ahead of threats.
```

---

### 🧩 What I Bring

- **Security monitoring:** deploying the Wazuh SIEM, investigating alerts, and mapping them to MITRE ATT&CK
- **Linux & the command line:** comfortable working in the terminal and administering Linux servers
- **Cloud & containers:** deploying and configuring services on AWS EC2 with Docker and Nginx
- **Secure configuration:** SSH key-only access, AWS Security Group rules, and keeping secrets out of code
- **Scripting & automation:** Python and Bash for automating tasks
- **Databases:** writing SQL queries and working with MySQL
- **Problem solving:** troubleshooting issues methodically until they're fixed

---

### 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=flat-square&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=3178C6)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=flat-square&logo=databricks&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-0d1117?style=flat-square&logo=gnubash&logoColor=4EAA25)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=4479A1)

**Tools & Platforms**

![AWS](https://img.shields.io/badge/AWS%20EC2-0d1117?style=flat-square&logo=amazonwebservices&logoColor=FF9900)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED)
![Wazuh](https://img.shields.io/badge/Wazuh-0d1117?style=flat-square&logo=wazuh&logoColor=3D8FF7)
![Nginx](https://img.shields.io/badge/Nginx-0d1117?style=flat-square&logo=nginx&logoColor=009639)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=FCC624)
![Git](https://img.shields.io/badge/Git-0d1117?style=flat-square&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=5FA04E)
![VS Code](https://img.shields.io/badge/VS%20Code-0d1117?style=flat-square&logo=visualstudiocode&logoColor=007ACC)

---

### 📂 Projects

#### 🛡️ [AWS Mini SOC](https://github.com/LucasJulioSanto/aws-mini-soc)

A small **Security Operations Center** lab in AWS: a public Ubuntu web server monitored by a separate **Wazuh** security server inside a custom VPC. It detected both simulated attacks and **real internet scanners** probing the server.

<p align="center">
  <img src="https://raw.githubusercontent.com/LucasJulioSanto/aws-mini-soc/main/aws-soc-picture.png" alt="Wazuh dashboard monitoring the soc-web-server agent" width="85%">
</p>

- Built a custom **VPC** with public subnets, an Internet Gateway, route tables, and Security Groups (SSH limited to my IP)
- Deployed **Wazuh Manager, Indexer, and Dashboard** and connected a Wazuh agent over **private VPC networking**
- Detected failed SSH logins, mapped by Wazuh to **MITRE ATT&CK** (Credential Access, Lateral Movement)
- Caught **real reconnaissance** from automated internet scanners, classified as **T1595.002 Vulnerability Scanning**
- Troubleshot an unsupported OS, a full disk (resized EBS from 8 GB to 40 GB), and a broken `dpkg` package state

`AWS EC2` · `VPC` · `Ubuntu` · `Wazuh` · `Nginx` · `MITRE ATT&CK`

#### ☁️ [AWS Docker Nginx Website](https://github.com/LucasJulioSanto/aws-docker-nginx-website)

A cybersecurity-themed personal website deployed on **AWS EC2** and served by **Nginx** running in a **Docker** container, built with security in mind from the start.

<p align="center">
  <img src="https://raw.githubusercontent.com/LucasJulioSanto/aws-docker-nginx-website/main/screenshot.png" alt="Screenshot of the AWS Docker Nginx website" width="85%">
</p>

- Launched and configured an Amazon Linux EC2 instance with SSH key-only access and an Elastic IP
- Containerized Nginx with a read-only bind mount and limited the web root to the `site/` folder so the `.git` directory is never exposed
- Set up Security Group rules for HTTP traffic and kept secrets out of the repo with `.gitignore`
- Troubleshot and resolved Docker port conflicts during deployment

`AWS EC2` · `Docker` · `Nginx` · `Linux` · `HTML/CSS/JavaScript` · `Git`

---

### 📈 GitHub Stats

<p align="center">
  <img src="./profile-summary-card-output/github_dark/0-profile-details.svg" alt="Profile details" width="100%">
</p>
<p align="center">
  <img src="./profile-summary-card-output/github_dark/3-stats.svg" alt="GitHub stats" width="49%">
  <img src="./profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="Repos per language" width="49%">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/LucasJulioSanto/LucasJulioSanto/output/github-snake-dark.svg" alt="Contribution snake">
</p>

---

### 🔐 Cybersecurity Interests

- Network security and traffic analysis
- Linux hardening and system administration
- Cloud security and secure deployment
- Incident response and threat detection

---

### 🚀 Currently

- 🎓 Completing the Computer Information Technology program at BCIT
- 🔎 Building more hands-on cybersecurity projects
- 🤝 Open to co-op, internship, and entry-level IT jobs

<details>
<summary><b>⚡ More about me</b></summary>

- 🌱 Currently learning: Wazuh rules, log analysis, and Linux hardening
- 💬 Ask me about: AWS, Wazuh, Docker, and Linux
- 🥾 Fun fact: I love hiking with my girlfriend and trying out new coffee shops ☕

</details>

---

<p align="center"><code>julio@bcit:~$ exit</code> · Thanks for stopping by!</p>
