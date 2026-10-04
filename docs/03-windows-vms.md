# Windows Virtual Machines

Deploy Windows Server and Windows client VMs.

## Tasks
- Install operating systems
- Rename systems
- Patch systems
- Configure addressing
- Install guest tools
- Validate time and networking
- Document VM purpose

## Validation
```powershell
hostname
Get-NetIPConfiguration
Get-ComputerInfo
```

## Evidence
Capture server/client desktops, hostnames, and sanitized IP configuration.
