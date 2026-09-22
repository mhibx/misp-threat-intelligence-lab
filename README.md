# MISP Threat Intelligence Lab

"What do we know about threats?"

Practical Threat Intelligence and CTI enrichment lab using MISP,
with Wazuh used for threat-hunting validation and SIEM context.

## What This Lab Covers

- Threat Intelligence
- MISP Event Management
- Threat Actor Analysis
- MITRE ATT&CK
- TTP Context
- Threat Hunting
- IOC / Observable Analysis
- SIEM Enrichment
- CTI-driven Investigation

## Workflow

Public Intelligence
        ↓
MISP
        ↓
Threat Actor / TTP Context
        ↓
Threat Hunting Hypothesis
        ↓
Wazuh
        ↓
Telemetry Validation
        ↓
Investigation

## Cases

### Case 01 — SVR / APT29 — Cloud Access Tactics

Source:
CISA AA24-057A

Focus:
- APT29 threat actor context
- MITRE ATT&CK T1110.001
- MITRE ATT&CK T1110.003
- MITRE ATT&CK T1090.002
- MISP Event & Galaxy
- Threat-hunting hypothesis
- Wazuh Event ID 4625
- Evidence-based assessment

[View Case →]

## Lab Environment

MISP
Wazuh
Windows endpoint
Ubuntu security server

## Key Principle

Threat intelligence provides context and hypotheses.
Telemetry and evidence determine what can actually be concluded
about the environment.
