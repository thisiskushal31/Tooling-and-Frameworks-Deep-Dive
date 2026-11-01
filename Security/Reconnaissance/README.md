# Reconnaissance

[← Security](../README.md)

OSINT, network discovery, surface mapping, and exposure search. **Lab / authorized targets only.**

Methodology (how recon works, defense, program order): [Security-Deep-Dive / Reconnaissance](https://github.com/thisiskushal31/Security-Deep-Dive/tree/main/Reconnaissance). This folder owns **install and first-use only** — do not re-teach program methodology here, and do not invent a second home for a tool that already has a folder (same rule as [n8n → Automation](../../Automation/n8n/README.md)).

Wire meaning of a scan → Networks `Security/8`.

## By capability

Labels for **routing**, not new directories. One product → one folder below; several programs may link the same folder.

| Capability | Tools (existing folders only) | Typical jobs |
|------------|-------------------------------|--------------|
| **Network scanners** | [Nmap](./Nmap/README.md) · [Masscan](./Masscan/README.md) | Host/port/service discovery; inventory confirmation; purple scan noise |
| **OSINT collectors** | [theHarvester](./theHarvester/README.md) · [Amass](./Amass/README.md) · [Maltego](./Maltego/README.md) · [SpiderFoot](./SpiderFoot/README.md) · [Recon-ng](./Recon-ng/README.md) | Public emails, hosts, link graphs, automated OSINT |
| **Web surface mappers** | [Gobuster](./Gobuster/README.md) · [ffuf](./ffuf/README.md) · [Nikto](./Nikto/README.md) · [Nuclei](./Nuclei/README.md) | Paths, vhosts, DNS brute, known-misconfig / template checks |
| **Exposure search** | [Shodan](./Shodan/README.md) | Internet-facing inventory for **owned / contracted** assets (ASM-style) |
| **Vuln scanners (overlap)** | [GVM](./GVM/README.md) · [Nuclei](./Nuclei/README.md) | After discovery — program depth in Security-Deep-Dive Vulnerability-Management |

## All tool folders

| Folder | Job |
|--------|-----|
| [Nmap](./Nmap/README.md) | Port / service scan — first lab door |
| [Masscan](./Masscan/README.md) | Fast port sweep |
| [theHarvester](./theHarvester/README.md) | Public emails / names / hosts |
| [Maltego](./Maltego/README.md) | Link analysis |
| [Shodan](./Shodan/README.md) | Internet-facing inventory (lab / owned assets) |
| [Recon-ng](./Recon-ng/README.md) | Recon framework |
| [Amass](./Amass/README.md) | Attack-surface mapping |
| [SpiderFoot](./SpiderFoot/README.md) | OSINT automation |
| [Nikto](./Nikto/README.md) | Web server scan |
| [Nuclei](./Nuclei/README.md) | Template vulns |
| [Gobuster](./Gobuster/README.md) | Dir / DNS brute |
| [ffuf](./ffuf/README.md) | Fuzzing |
| [GVM](./GVM/README.md) | OpenVAS / vulnerability scan |
