# Home SIEM Lab with Wazuh on Rocky Linux

A small endpoint monitoring lab built to learn SOC workflows. 
Used to collect logs, review vulnerabilities, and write custom detection rules.

## Goals:
- Get hands-on experience with a widely used SIEM
- Practice patching vulnerabilities on machines I own
- Build and test custom detection rules
- Document the process

## Architecture:
- Wazuh Server: HP EliteDesk 800 G3 Mini, 16 GB RAM, Rocky Linux
- Agents: Desktop on CachyOS & laptop on Arch Linux
- Network: LAN only

## Working:
- Wazuh server & dashboard functional
- Agents installed & successfully reporting to server

## What's Next:
- Installing agents on lab VMs from my TrueNAS server
- Exploit lab VM & see effects on SIEM
- ClamAV logs integration
- Custom alert rules
