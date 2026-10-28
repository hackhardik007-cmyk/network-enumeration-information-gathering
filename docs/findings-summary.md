# Findings Summary

## Summary

This practical assignment explored post-scan enumeration in an isolated VMware lab using Metasploitable2. The work focused on gathering structured details about hosts, services, SMB shares, user/domain information, public-source OSINT, and vulnerability scanner findings.

## Observations

- Enumeration can expose more actionable context than a basic open-port list, including service details and share configuration.
- Legacy services and overly permissive shares should be reviewed and restricted where not required.
- Scanner output requires validation and context; a detected issue is not automatically a confirmed exploitable vulnerability.
- OSINT and internal-lab enumeration have different scopes and authorization considerations.

## Defensive Implications

- Reduce unnecessary exposure and review insecure defaults.
- Improve authentication, patching, endpoint visibility, and logging based on the relevant risk.
- Validate suspected issues before assigning severity or declaring exploitability.
- Preserve evidence and maintain a clear scope during any security assessment.

## Limitations

The report reflects a deliberately vulnerable training target and educational exercises. No claims are made about production environments. Public release should omit lab IPs, raw scanner output, credentials, and unredacted screenshots.

## Publication Notes

This summary intentionally avoids raw target details, credentials, payloads, and unredacted evidence. Do not add those materials to a public repository.
