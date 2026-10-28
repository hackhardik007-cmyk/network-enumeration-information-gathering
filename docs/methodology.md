# Methodology

## Project

CEH Module 4: Network Enumeration Assessment

## Environment and Scope

This practical assignment explored post-scan enumeration in an isolated VMware lab using Metasploitable2. The work focused on gathering structured details about hosts, services, SMB shares, user/domain information, public-source OSINT, and vulnerability scanner findings.

## Tools and Their Purpose

- Kali Linux
- Nmap
- SMBclient
- Enum4linux
- theHarvester
- Nessus Essentials
- VMware Workstation
- Metasploitable2

## Workflow

1. Verified target availability and performed host discovery.
2. Enumerated open ports, service banners, and operating-system indicators with Nmap.
3. Reviewed SMB share exposure with SMBclient and Enum4linux within the lab.
4. Explored theHarvester as an OSINT collection tool and documented the difference between public-source collection and active target enumeration.
5. Used Nessus Essentials as a vulnerability-scanning component and documented findings and limitations.

## Validation and Safety

- Treat tool output as an observation that may require manual validation.
- Avoid publishing secrets, account details, private IPs, full scan outputs, or unredacted screenshots.
- Keep any follow-up testing inside an explicitly authorized lab.
- Do not infer that a system is secure solely because a scan did not report a critical finding.
