# Threat Hunting

Proactive threat hunting queries, scenarios, and methodologies for Microsoft Sentinel and Microsoft 365 Defender.

## Structure

- `queries/` - Hunting queries organized by threat type
- `scenarios/` - Complete hunting scenarios with context
- `notebooks/` - Jupyter notebooks for advanced hunting
- `methodologies/` - Hunting frameworks and approaches

## Hunting Categories

- **Initial Access** - Phishing, credential theft, external remote services
- **Execution** - Suspicious processes, script execution, command-line activity
- **Persistence** - Scheduled tasks, registry modifications, startup items
- **Privilege Escalation** - Token manipulation, abuse of elevation mechanisms
- **Defense Evasion** - Disabling security tools, file deletion, obfuscation
- **Credential Access** - Credential dumping, brute force, keylogging
- **Discovery** - System information gathering, network scanning
- **Lateral Movement** - Remote services, pass-the-hash, RDP
- **Collection** - Data staging, archive collection
- **Exfiltration** - Data transfer, command and control
- **Impact** - Data destruction, service disruption

## Hunting Workflow

1. Hypothesis formation
2. Query development
3. Data analysis
4. Investigation
5. Documentation

