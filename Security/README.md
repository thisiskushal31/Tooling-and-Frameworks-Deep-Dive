# Security software

[← README](../README.md)

Named **lab software** (install + first use). The *program* (CIA, AppSec, SOC, GRC, PTES phases) stays in [Security-Deep-Dive](https://github.com/thisiskushal31/Security-Deep-Dive/blob/main/README.md). Packet depth stays in Networks. **Isolated lab only — never scan the public internet.**

### One tool, one home (no duplication)

| Rule | Example |
|------|---------|
| One product → **one** folder in this repo | [Nmap](./Reconnaissance/Nmap/README.md) serves recon, vuln, and blue — do not fork copies |
| Already elsewhere in Tooling → **link**, do not re-create under Security | [n8n](../Automation/n8n/README.md) lives in Automation — not here |
| Capability labels = README tables, not new trees | See [Reconnaissance — By capability](./Reconnaissance/README.md) |
| Methodology / defense depth | Security-Deep-Dive links here; never paste full install manuals there |

| Job | Folder |
|-----|--------|
| Find systems and public facts | [Reconnaissance/](./Reconnaissance/README.md) |
| Attack in a lab you own | [Offensive/](./Offensive/README.md) |
| Capture, memory, blue-team kit | [Defensive/](./Defensive/README.md) |
| Binaries / firmware | [Reverse-Engineering/](./Reverse-Engineering/README.md) |

Workflow automation (n8n) is not a security product → [../Automation/](../Automation/README.md).
