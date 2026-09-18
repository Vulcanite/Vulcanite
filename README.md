<h1 align="center">Hi, I'm Amish Thekke Parambil</h1>

<h3 align="center">Security Product Engineer | MComp Infocomm Security @ NUS</h3>

<p align="center">
  <a href="https://amishtp.tech"><img src="https://img.shields.io/badge/Portfolio-amishtp.tech-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/amish-thekke-parambil/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:amishtp147@outlook.com"><img src="https://img.shields.io/badge/Email-amishtp147%40outlook.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://files.amishtp.tech/Amish-Thekke-Parambil-Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-4B5563?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume" /></a>
</p>

---

## 👨‍💻 About Me

I am a **security product engineer** with **three years of industry experience** taking security software from design to production, including deployments on customer infrastructure. My work sits between network security, Linux systems, and the tooling that operates them.

- 🎓 Master of Computing, Infocomm Security — **National University of Singapore** (2025 – present)
- 🔬 Research on **provenance-based intrusion detection for Linux** (eBPF, auditd, container runtimes) under Prof. Liang Zhenkai
- 🛡️ Shipped **WAF, anti-DDoS, and remote access products** to enterprise and government customers
- 🔧 Build open-source tools for **web application defense and host investigation**
- 🏆 Best Performer (Engineering) of the Year 2024 · Smart India Hackathon 2022 Winner
- 📍 Singapore

---

## 🛠️ Tech Stack

### Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### Security & Networking

`ModSecurity / CRS` `NGINX modules` `WAF & Anti-DDoS operations` `eBPF & auditd` `Threat intelligence pipelines` `SSL inspection` `Remote access (SSH / RDP / VNC gateways)`

### Backend & Frameworks

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

### Infrastructure & Tooling

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![VictoriaMetrics](https://img.shields.io/badge/VictoriaMetrics-621773?style=flat-square)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

---

## 🚀 Experience Highlights

Three years at Haltdos, from intern to L-3 software developer.

| Area | What I did |
| --- | --- |
| 🔐 Remote Access | Sole engineer on a ground-up rewrite of the Remote Access Gateway: MFA, fine-grained access policies, browser-based SSH/RDP/VNC, session auditing, and a Rust client with endpoint validation |
| 🌐 Web Security | Built a Secure Web Proxy with dual deployment modes, SSL inspection, and domain filtering, deployed for enterprise and government clients |
| 🤝 Customer Ownership | Account manager for two enterprise WAF / anti-DDoS accounts across on-premises, SaaS, and private cloud |
| 🧱 Platform | Migrated the product line to RHEL; co-led Pro WAF — auto-upgrade system, licensing, and multi-platform support |
| ⚙️ Release Engineering | Replaced mixed-language release scripts with a Go CLI; Jenkins CI replaced a manual VM-based build process |
| 📈 Monitoring | Grafana + VictoriaMetrics monitoring for distributed WAF nodes across cloud providers, with real-time alerting |
| 🧠 Threat Intelligence | Built the feed aggregating malicious IPs, bad bots, and TOR exit nodes into detection and blocking pipelines |
| 👥 Mentoring | Mentored 6 interns on security and infrastructure work; 4 were hired full-time |

---

## 📂 Selected Projects

| Project | Stack | What it does |
| --- | --- | --- |
| [**ngx_json_guard**](https://github.com/Vulcanite/ngx_json_guard) | C, NGINX, ModSecurity | NGINX module that checks large JSON request bodies against structural safety limits before ModSecurity inspects them, so full CRS inspection of large JSON is safe |
| [**waf-tuner**](https://github.com/Vulcanite/waf-tuner) | Python, FastAPI, Next.js | Human review queue for ModSecurity CRS alerts. A model classifies evidence and drafts parameter-scoped exceptions; the operator decides, the model never touches edge config |
| [**ThreatFetch**](https://github.com/Vulcanite/ThreatFetch) | Go | IOC triage from the terminal. Queries providers, normalizes evidence, and computes a deterministic threat score |
| [**auditstream**](https://github.com/Vulcanite/auditstream) | Python, FastAPI, NetworkX | Ingests auditd or live telemetry, builds a provenance graph, reduces noise, and produces investigation findings |
| [**sshnav**](https://github.com/Vulcanite/sshnav) | Rust, SQLite | Fast local SSH inventory navigator and launcher with fuzzy TUI and OpenSSH config import |
| [**vllm-gpu-manager**](https://github.com/Vulcanite/vllm-gpu-manager) | Go, Docker, React | Single-binary CLI and web console for running vLLM servers on NVIDIA hosts: GPU placement, VRAM checks, KV-cache estimation |

---

## 🔬 Research

**National University of Singapore · Supervisor: [Prof. Liang Zhenkai](https://www.comp.nus.edu.sg/cs/people/liangzk/)**

- **Heimdall** — a multi-source provenance collection agent for heterogeneous Linux environments. CO-RE portable Go daemon collecting from eBPF, the Linux audit subsystem, and container runtimes, with a SHA256-based StableID for cross-source process identity.
- **PIR (Provenance Intermediate Representation)** — a portability contract for provenance-based intrusion detection, derived from the implicit assumptions in existing detection algorithms and validated by a cross-collector F1 experiment.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Vulcanite&show_icons=true&theme=github_dark&hide_border=true&hide_title=true" alt="GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vulcanite&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top languages" height="165" />
</p>

---

## 🤝 Connect With Me

<p align="center">
  <a href="https://amishtp.tech">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/amish-thekke-parambil/">LinkedIn</a> ·
  <a href="mailto:amishtp147@outlook.com">Email</a> ·
  <a href="https://files.amishtp.tech/Amish-Thekke-Parambil-Resume.pdf">Resume</a>
</p>

<p align="center"><b>Open to security engineering roles and research collaborations in systems and network security.</b></p>
