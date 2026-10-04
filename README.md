# Home Virtualization Lab

**Infrastructure • VMware • Windows • Linux • Networking**

## Project Summary
Design and operate a multi-VM environment that demonstrates practical virtualization, resource allocation, network design, lifecycle management, and troubleshooting.

This repository is structured as a portfolio project: architecture, implementation, validation, security considerations, troubleshooting, and screenshot evidence are documented so the work can be reproduced and discussed in a technical interview.

## Architecture
```text
Physical Host
     |
VMware Hypervisor
     |
Virtual Network
 +---+-----------+-----------+
 |               |           |
Windows Server  Windows 11  Linux Server
 |               |           |
Infrastructure  Endpoint    Services
```

## Core Skills
- VMware
- Virtual Networking
- Windows
- Linux
- Snapshots
- Resource Management
- Troubleshooting

## Project Documentation
1. [Host And Network Design](docs/01-host-and-network-design.md)
2. [Vmware Configuration](docs/02-vmware-configuration.md)
3. [Windows Vms](docs/03-windows-vms.md)
4. [Linux Vms](docs/04-linux-vms.md)
5. [Virtual Networking](docs/05-virtual-networking.md)
6. [Snapshots And Recovery](docs/06-snapshots-and-recovery.md)
7. [Monitoring And Troubleshooting](docs/07-monitoring-and-troubleshooting.md)
8. [Screenshot Evidence](images/README.md)

## Validation Standard
For every major component I document:
1. **Purpose** — why the component exists.
2. **Configuration** — how I deployed it.
3. **Validation** — commands/tests proving it works.
4. **Troubleshooting** — likely failure points and diagnostic steps.
5. **Security** — how access and exposure are reduced.
6. **Evidence** — sanitized screenshots of the completed work.

## Portfolio Safety
No real passwords, secrets, API tokens, private keys, product keys, recovery codes, personal data, or sensitive public-facing configuration should be committed.

## What This Project Demonstrates
Rather than only listing technologies on a résumé, this lab provides evidence of planning, implementation, administration, documentation, troubleshooting, and security-minded decision making.

## Author
**Alexis Wiscovitch** — [@Alexis-error404](https://github.com/Alexis-error404)
