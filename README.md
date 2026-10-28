# CEH Module 4: Network Enumeration Assessment

> Coursework project | CEH v12 curriculum | Intellipaat

## Overview

This practical assignment explored post-scan enumeration in an isolated VMware lab using Metasploitable2. The work focused on gathering structured details about hosts, services, SMB shares, user/domain information, public-source OSINT, and vulnerability scanner findings.

## Objectives

- Document the methodology and observations from the course lab.
- Explain security implications in clear, defensible terms.
- Connect observations to practical defensive recommendations.
- Keep public documentation sanitized and reproducible at a high level.

## Lab and Tools

- Kali Linux
- Nmap
- SMBclient
- Enum4linux
- theHarvester
- Nessus Essentials
- VMware Workstation
- Metasploitable2

## Methodology

1. Verified target availability and performed host discovery.
2. Enumerated open ports, service banners, and operating-system indicators with Nmap.
3. Reviewed SMB share exposure with SMBclient and Enum4linux within the lab.
4. Explored theHarvester as an OSINT collection tool and documented the difference between public-source collection and active target enumeration.
5. Used Nessus Essentials as a vulnerability-scanning component and documented findings and limitations.

## Key Findings

- Enumeration can expose more actionable context than a basic open-port list, including service details and share configuration.
- Legacy services and overly permissive shares should be reviewed and restricted where not required.
- Scanner output requires validation and context; a detected issue is not automatically a confirmed exploitable vulnerability.
- OSINT and internal-lab enumeration have different scopes and authorization considerations.

## Defensive Recommendations

- Apply least privilege and remove or restrict services that are not required.
- Keep operating systems, applications, and security tools updated.
- Use strong unique passwords and multifactor authentication where available.
- Centralize and review relevant endpoint, authentication, and network logs.
- Validate scanner or tool output before treating it as a confirmed vulnerability.
- Preserve evidence and document scope during incident investigation.

## Scope and Limitations

The report reflects a deliberately vulnerable training target and educational exercises. No claims are made about production environments. Public release should omit lab IPs, raw scanner output, credentials, and unredacted screenshots.

## Ethics and Safety

All hands-on activity described here was coursework conducted in a lab context. Only assess systems for which you have explicit authorization. This repository contains documentation only; it does not distribute payloads, credentials, malware, or raw target scan data.

## Repository Structure

- `docs/methodology.md` — concise workflow and tool purpose.
- `docs/findings-summary.md` — summarized observations, implications, and limitations.
- `evidence/README.md` — guidance for adding sanitized screenshots, if permitted.
- `.gitignore` — excludes common temporary and sensitive files.

## Coursework Disclaimer
