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
amish@sg:~$ systemctl list-units --type=shipped        # three years at Haltdos, intern → L-3

  UNIT                              ACTIVE   DESCRIPTION
● remote-access-gateway.service     active   ground-up rewrite as the only engineer on the product:
                                             MFA, fine-grained access policies, browser SSH/RDP/VNC,
                                             session auditing, Rust client with endpoint validation
● secure-web-proxy.service          active   dual deployment modes, SSL inspection, domain filtering;
                                             deployed for enterprise and government clients
● pro-waf.service                   active   co-led: auto-upgrade system, licensing and subscription
                                             management, multi-platform builds
● enterprise-accounts.target        active   account manager for two enterprise WAF / anti-DDoS customers
                                             across on-premises, SaaS, and private cloud
● threat-intel-feed.service         active   malicious IPs, bad bots, TOR exit nodes → detection pipelines
● rhel-migration.service            active   moved the whole product line onto Red Hat Enterprise Linux
● release-cli.service               active   one Go CLI replaced mixed-language release scripts;
                                             Jenkins CI replaced manual VM builds
● monitoring.service                active   Grafana + VictoriaMetrics for distributed WAF nodes, real-time alerting
● mentoring.service                 active   6 interns; 4 hired full-time

9 loaded units listed.
```

<br>

```console
amish@sg:~$ cat ~/.config/stack.toml
[languages]   go · rust · c · python · java · bash · javascript
[security]    modsecurity/crs · nginx modules · waf & anti-ddos ops · ebpf & auditd · threat intel pipelines
[backend]     spring boot · fastapi · django · next.js · react
[infra]       linux · docker · kubernetes · nginx · jenkins · grafana · victoriametrics · elasticsearch
```

<br>

### `ls ~/projects`

Tools for people who run WAFs and investigate hosts. Each one exists because I wanted it at 2 a.m. and it didn't.

| | | |
| --- | --- | --- |
| [**ngx_json_guard**](https://github.com/Vulcanite/ngx_json_guard) | `C` `NGINX` | Checks large JSON request bodies against structural limits *before* ModSecurity sees them, so full CRS inspection of big JSON is safe instead of a DoS vector. |
| [**waf-tuner**](https://github.com/Vulcanite/waf-tuner) | `Python` `FastAPI` `Next.js` | Human review queue for CRS alerts. A model classifies evidence and drafts parameter-scoped exceptions. The operator decides. The model never writes edge config. |
| [**ThreatFetch**](https://github.com/Vulcanite/ThreatFetch) | `Go` | IOC triage from the terminal. One binary, many providers, one deterministic threat score. |
| [**auditstream**](https://github.com/Vulcanite/auditstream) | `Python` `NetworkX` | auditd or live telemetry in, provenance graph out. Noise reduction and investigation findings with the graph as the evidence trail. |
| [**sshnav**](https://github.com/Vulcanite/sshnav) | `Rust` `SQLite` | Fuzzy TUI over your SSH inventory. Imports OpenSSH config, including `Host *` inheritance. |
| [**vllm-gpu-manager**](https://github.com/Vulcanite/vllm-gpu-manager) | `Go` `Docker` `React` | Single binary for running vLLM on NVIDIA hosts: GPU placement, VRAM launch checks, KV-cache estimation. |

<br>

```console
amish@sg:~$ journalctl -u awards --no-pager
Sep 2024  haltdos    Best Performer (Engineering) of the Year
Sep 2023  haltdos    Best Motivated Employee Award
Aug 2022  gov.in     Smart India Hackathon 2022 — Winner
```

<br>

```console
amish@sg:~$ cat /etc/rules.d/how-i-work.conf
# read the code before changing it
# ship to a real machine, not a demo
# the model can draft; a person decides
# if it needs a runbook, it needs a fix

amish@sg:~$ exit
```

<p align="center">
  <a href="https://amishtp.tech">amishtp.tech</a> · <a href="https://www.linkedin.com/in/amish-thekke-parambil/">LinkedIn</a> · <a href="mailto:amishtp147@outlook.com">amishtp147@outlook.com</a>
</p>
