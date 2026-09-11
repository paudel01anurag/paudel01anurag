# Anurag Paudel — Cybersecurity & Risk Portfolio 🔐

Cybersecurity practitioner with an engineering background and an MBA, working where security
meets the business: risk, governance, third-party assurance and vulnerability management.
Before this I co-founded and ran a technology company that won 13 government contracts in
Nepal, which is where I learned what a control actually costs the people who have to live
with it.

**Currently seeking roles in GRC, third-party risk, security analysis or vulnerability management.**

---

## 🌐 Web Security Research

**[Multi-Vector Web Risk Analysis — 99,987 Domain Study](https://github.com/paudel01anurag/web-security-header-analysis)** — master's final project

A passive five-vector risk assessment of 99,987 domains from the Tranco list, scoring HTTP
security headers, DNS and email authentication, TLS, attack surface and third-party
dependency integrity under CVSS-inspired weighting. 99.99% scan coverage.

> **94.2% of sites loading external JavaScript ship no Subresource Integrity hashes.** Of
> 35,083 sites pulling in third-party code, only 315 verify it. That is an unguarded
> supply-chain path across almost the entire sample.
>
> **95.1% of sites would look at least 20 points safer under any single-vector audit** than
> under the composite score. One tool is not an assessment.

DNSSEC sits at 4.9% adoption and Content-Security-Policy at 16.4%, while TLS 1.3 reaches
88.3% and not a single domain negotiated TLS 1.1 or below. TLS modernisation succeeded.
Everything else stalled.

[Full findings report](https://github.com/paudel01anurag/web-security-header-analysis/blob/main/analysis/findings.md)
· [Figures](https://github.com/paudel01anurag/web-security-header-analysis/tree/main/analysis/figures)
· [Data tables](https://github.com/paudel01anurag/web-security-header-analysis/tree/main/analysis/tables)

## 🔍 Digital Forensics & Incident Response

**[MySQL Database Extortion Case Study](https://github.com/paudel01anurag/mysql-dfir-case-study)**

Full incident response lifecycle on a controlled lab compromise, investigated with KQL,
Microsoft Defender for Endpoint and MySQL audit logs, and taken through containment,
credential rotation, hardening, verified backup restoration and recovery validation.

The report deliberately separates confirmed findings from investigative leads and evidence
gaps. It does not claim exfiltration or host persistence, because the telemetry does not
support either.

## 🎯 Threat Hunting

**[Threat Hunting Lab](https://github.com/paudel01anurag/threat-hunting-lab)** — KQL in
Microsoft Sentinel and Defender for Endpoint

Three completed hunts on the LogN Pacific Cyber Range, 98 flags and 9,300 points, with no
alerts, dashboards or starting indicators. Phishing through to domain compromise and source
code theft; MFA fatigue through to business email compromise and attempted wire fraud;
exposed RDP through to malware concealed inside a legitimate Windows service.

Written up as method rather than answers, so nothing here spoils a live hunt.

## ⚠️ Vulnerability Management

**Tenable vulnerability management program** — *lab work, write-up in progress*

Scan coverage validation, asset and tag hygiene, and remediation prioritised by business
exposure rather than raw CVSS.

## 💻 Software & Product

**[DueKhata — Subscription Tracker](https://github.com/paudel01anurag/duekhata-subscription-tracker)**

A Windows desktop app I built and ship: single-file executable, 135 unit tests on every
push, changelog, MIT licence. Fully local by design — no account, no server, no network
access.

---

## 🎓 Education

- **M.S. Informatics**, concentration in Cybersecurity — University of Louisiana at Lafayette, 2026
- **MBA, Information Technology** — Tribhuvan University, Nepal, 2022
- **B.E. Computer Engineering** — Tribhuvan University, Nepal, 2019

## 🛠️ Tools & Technologies

`Microsoft Sentinel` · `Defender for Endpoint` · `KQL` · `Tenable` · `Azure` · `Entra ID` ·
`Python` · `PowerShell` · `SQL` · `MITRE ATT&CK` · `NIST CSF`

---

## 🤝 Connect

- 📧 paudel01anurag@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/paudel01anurag/)
