# Security Operations, DFIR & Detection Engineering Portfolio

I am Nnanna Adaobi Evelyn, a cybersecurity practitioner working across
SOC analysis, incident response/DFIR, detection engineering, threat hunting
and security telemetry engineering.

My work focuses on evidence-driven investigation: preserving what the
underlying telemetry actually supports, correlating activity across sources,
testing detection logic against failure cases, and producing findings that
remain traceable to source evidence.

## Flagship Project

### TraceSOC — Provenance-First SOC/DFIR Evidence-Reconstruction Engine

TraceSOC is an original security engineering project built to reconstruct
analytical findings from heterogeneous raw evidence while preserving
provenance throughout the analysis chain.

The system works across email, packet, Zeek, Sysmon, PowerShell Operational
and Windows Security evidence and supports normalization, detection,
bounded cross-source correlation, evidence graphs, findings, narratives
and reverse tracing to original artifacts.

Key validated results include:

- 5,442 / 5,442 canonical observations with raw-evidence locators
- External Zeek reconciliation: 23,145 / 23,145 records
- Sealed holdout reconciliation: 156,458 / 156,458 records
- 524 / 524 regression tests passed
- 4 / 4 public acceptance classes passed
- Two clean reproductions produced the same 11 core output hashes
- 198,463-record measured workload completed on an approximately 8 GB machine

> Public documentation presents the engineering approach and independently
> supportable results. Private programme fixtures and controlled assessment
> material are not published.

## Selected Projects

### 8GB SOC Lab — Multi-Endpoint Wazuh SIEM

Engineered and operated a Wazuh SOC environment across Windows and Linux
endpoints on an 8GB laptop.

The project included:

- Wazuh Manager deployment
- Windows and Linux agent onboarding
- Centralized endpoint telemetry
- Authentication and host-event investigation
- File Integrity Monitoring and audit telemetry
- Controlled reverse-shell/listener testing
- Troubleshooting virtualization and service failures under severe
  resource constraints

### GCP + Elastic Security — SSH Investigation

Deployed an Ubuntu workload on Google Cloud Platform and onboarded
authentication, system, network and process telemetry into Elastic Security.

Investigated repeated SSH authentication failures followed by successful
privileged access using KQL, mapped observed behavior to MITRE ATT&CK,
and implemented SSH hardening and access restrictions.

## Assessed Security Engineering Work

Through Ubuntu Bridge Initiative's SOC Analysis programme, my work has
included:

- Threat-hunting pipelines with Python and DuckDB
- Security-telemetry normalization and identity resolution
- Deception-sensor analysis
- STIX 2.1, Sigma and Suricata outputs
- Network detection engineering with containerlab, FRR and nftables
- Detection-as-code and adversarial mutation testing
- Multi-source incident reconstruction and DFIR

I progressed to Stage 9B finalist status with cumulative standing of
1st of 18 in the SOC Analysis track.

## Technical Areas

**SOC / DFIR**
Incident investigation, timeline reconstruction, evidence preservation,
provenance, threat hunting, IOC validation, authentication/process/network
analysis

**Detection Engineering**
Detection-as-code, semantic detection, multi-event correlation, benign
controls, regression testing, MITRE ATT&CK

**Security Telemetry**
Wazuh, Elastic Security, Sysmon, Zeek, Suricata, Windows Security,
PowerShell Operational, PCAP

**Engineering**
Python, DuckDB/SQL, KQL, PowerShell, Linux, Git, containerlab, FRR,
nftables

## Technical Writing & Advocacy

I document practical cybersecurity work and lessons through technical
writing, including my 8GB Wazuh SOC Lab project.

I have also delivered cybersecurity and digital-safety awareness sessions
through the Women Techsters Initiative across 7 schools, reaching 600+
students.

## Connect

- LinkedIn: linkedin.com/in/adaobievelyn
- Medium: medium.com/@nnanna.adaobi.e
