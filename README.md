<h1 align="center">Amish Thekke Parambil</h1>
<p align="center">Security Product Engineer · Singapore</p>

<p align="center">
  <a href="https://amishtp.tech"><img src="https://img.shields.io/badge/amishtp.tech-0A0A0A?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/amish-thekke-parambil/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:amishtp147@outlook.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://files.amishtp.tech/Amish-Thekke-Parambil-Resume.pdf"><img src="https://img.shields.io/badge/Resume-4B5563?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Resume" /></a>
</p>

```console
amish@sg:~$ whoami
security product engineer. three years shipping security software,
back when your only co-programmer was the person at the next desk.

amish@sg:~$ cat /etc/motd
Now at NUS pursuing a Master's in Infocomm Security.
I build tools for people who run WAFs and investigate Linux hosts.

amish@sg:~$ uptime
 2022–2025 industry · 2025– NUS · load average: network security, linux systems, the tooling that operates them
```

<br>

```console
amish@sg:~$ systemctl list-units --type=shipped
```
```diff
# three years at Haltdos, intern → L-3

+ ● remote-access-gateway.service      active
      ground-up rewrite as the only engineer on the product: MFA, fine-grained
      access policies, browser SSH/RDP/VNC, session auditing, Rust client with
      endpoint validation

+ ● secure-web-proxy.service           active
      dual deployment modes, SSL inspection, domain filtering;
      deployed for enterprise and government clients

+ ● pro-waf.service                    active
      co-led: auto-upgrade system, licensing and subscription management,
      multi-platform builds

+ ● enterprise-accounts.target         active
      account manager for two enterprise WAF / anti-DDoS customers
      across on-premises, SaaS, and private cloud

+ ● threat-intel-feed.service          active
      malicious IPs, bad bots, TOR exit nodes → detection pipelines

+ ● rhel-migration.service             active
      moved the whole product line onto Red Hat Enterprise Linux

+ ● release-cli.service                active
      one Go CLI replaced mixed-language release scripts;
      Jenkins CI replaced manual VM builds

+ ● monitoring.service                 active
      Grafana + VictoriaMetrics for distributed WAF nodes, real-time alerting

+ ● mentoring.service                  active
      6 interns; 4 hired full-time

@@ 9 loaded units listed. 0 failed. @@
```

<br>

```console
amish@sg:~$ cat ~/.config/stack.toml
```
```toml
[languages]
primary   = ["go", "rust", "c", "python"]
also      = ["java", "bash", "javascript"]

[security]
web       = ["modsecurity/crs", "nginx modules", "waf & anti-ddos operations"]
host      = ["ebpf", "auditd", "threat intelligence pipelines"]

[backend]
frameworks = ["spring boot", "fastapi", "django", "next.js", "react"]

[infra]
runtime    = ["linux", "docker", "kubernetes", "nginx"]
delivery   = ["jenkins", "grafana", "victoriametrics", "elasticsearch"]
```

<br>

### `ls ~/projects`

Tools for people who run WAFs and investigate hosts. Each one exists because I wanted it and AI makes it easy to develop and build.

| Project | Stack | What it does |
| --- | --- | --- |
| [**ngx_json_guard**](https://github.com/Vulcanite/ngx_json_guard) | ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white) | Checks large JSON request bodies against structural limits *before* ModSecurity sees them, so full CRS inspection of big JSON is safe instead of a DoS vector. |
| [**waf-tuner**](https://github.com/Vulcanite/waf-tuner) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) | Human review queue for CRS alerts. A model classifies evidence and drafts parameter-scoped exceptions. The operator decides. The model never writes edge config. |
| [**sshnav**](https://github.com/Vulcanite/sshnav) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) | Fuzzy TUI over your SSH inventory. Imports OpenSSH config, including `Host *` inheritance. |
| [**vllm-gpu-manager**](https://github.com/Vulcanite/vllm-gpu-manager) | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) | Single binary for running vLLM on NVIDIA hosts: GPU placement, VRAM launch checks, KV-cache estimation. |
| [**wg-manager**](https://github.com/Vulcanite/wg-manager) | ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white) | One Bash file that sets up a WireGuard server and manages its users: QR codes, traffic, and IPv6 routed into the tunnel so it can't leak. |

<br>

```console
amish@sg:~$ cat ~/contact
Amish Thekke Parambil — Singapore
Email is the fastest way to reach me. LinkedIn works too.

amish@sg:~$ exit
```

<p align="center">
  <a href="mailto:amishtp147@outlook.com"><img src="https://img.shields.io/badge/Email_me-amishtp147%40outlook.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Amish" /></a>
  <a href="https://www.linkedin.com/in/amish-thekke-parambil/"><img src="https://img.shields.io/badge/Message_me_on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Amish on LinkedIn" /></a>
  <a href="https://amishtp.tech"><img src="https://img.shields.io/badge/My_site-amishtp.tech-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Amish's portfolio" /></a>
</p>
