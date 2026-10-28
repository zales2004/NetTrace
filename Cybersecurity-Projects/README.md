# Cybersecurity Projects — Alen Sales K S

This directory is a **portfolio index** linking to my cybersecurity repositories. GitHub repositories are separate projects and cannot be nested inside a folder on my profile, so this index groups them in one place without moving or breaking their history.

> Focus: Networking • Linux & System Administration • SOC / Blue Team • VAPT • Security Engineering

## Networking & Network Security

- [NetTrace — Network Traffic Analysis & Wireshark](https://github.com/zales2004/NetTrace)
  - PCAP analysis, DNS, TCP, HTTP, TLS/QUIC, retransmissions, and evidence-based findings.

## SOC & Blue Team

- [Enterprise Active Directory SOC & PAM Lab](https://github.com/zales2004/Enterprise-Active-Directory-Pam-Soc-Lab)
  - Windows Server, Active Directory, Splunk, Windows security events, privileged group monitoring, and firewall telemetry.
- [Splunk SOC L1 Incident Investigation](https://github.com/zales2004/splunk-soc-l1-incident-investigation)
  - Authentication investigation, SPL searches, suspicious login correlation, and dashboarding.
- [SOC Alert Triage & Investigation](https://github.com/zales2004/soc-alert-triage-investigation-thm-Soc-simulator)
  - Alert classification, investigation workflow, phishing triage, and case documentation.
- [Greenholt Phishing Investigation](https://github.com/zales2004/greenholt-phishing-investigation)
  - Email/header analysis, attachment investigation, IOCs, threat intelligence, and ATT&CK mapping.

## VAPT & Authorized Lab Walkthroughs

- [CyberSploit 1](https://github.com/zales2004/cybersploit-1-ctf-walkthrough)
- [CyberSploit 2](https://github.com/zales2004/cybersploit-2-ctf-walkthrough)
- [Metasploitable 2](https://github.com/zales2004/metasploitable-2-ctf-walkthrough)
- [Sunset: Noontide](https://github.com/zales2004/sunset-noontide-pentesting)

These write-ups are for authorized, intentionally vulnerable training environments. Always verify scope and permission before testing systems.

## Security Fundamentals

- [Simple Password Strength Checker](https://github.com/zales2004/Simple-Password-Strength-Checker)

## Other Software & Research

- [REMEDYROOT](https://github.com/zales2004/Remedy-Root) — medicinal plant identification using deep learning.
- [Django Expense Tracker](https://github.com/zales2004/django-expense-tracker) — web application project.

## In Progress: AegisTrace

**AegisTrace** is my planned evidence-grounded AI SOC project. The intended workflow is to collect and normalize lab telemetry, detect suspicious sequences, correlate events into a timeline, distinguish observations from hypotheses, map supported behavior to MITRE ATT&CK, and recommend proportionate defensive actions.

Progress and claims will be documented as the features are actually implemented and tested.

## Investigation principles

1. Preserve evidence and record timestamps, hosts, users, and relevant indicators.
2. Correlate events rather than treating every alert in isolation.
3. Clearly separate observed facts from analyst hypotheses.
4. Record limitations and validation results.
5. Test only in authorized labs or on systems with explicit permission.
