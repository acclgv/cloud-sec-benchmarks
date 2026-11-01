# Cloud Security Benchmarks & CIS Policy-as-Code

[![CIS AWS Benchmark](https://img.shields.io/badge/CIS-AWS_v3.0-FF9900?style=flat-square&logo=amazon-aws)](https://www.cisecurity.org/)
[![CIS Azure Benchmark](https://img.shields.io/badge/CIS-Azure_v2.1-0078D4?style=flat-square&logo=microsoft-azure)](https://www.cisecurity.org/)
[![CSPM Compliance](https://img.shields.io/badge/CSPM-Continuous_Validation-success?style=flat-square)](https://github.com/acclgv/cloud-sec-benchmarks)

Automated multi-cloud security baseline benchmarks and Policy-as-Code posture evaluation rules for enterprise cloud architectures (AWS & Azure). Maintained by Luis García Villena (Accenture Security Transformation).

## Architecture & Scope
- **Identity & Access Management (IAM)**: Root account MFA, credential rotation, least-privilege role boundaries.
- **Data Protection & Storage**: S3 bucket policies, EBS default encryption, Azure Storage TLS 1.3 enforcement.
- **Logging & Threat Detection**: CloudTrail multi-region validation, GuardDuty, Azure Monitor alerts, Security Hub.
- **Network Hardening**: Default VPC restrictions, NSG inbound rules, public IP audit.

## Continuous Telemetry
Audits are evaluated periodically against the latest CIS benchmarks and cloud provider updates. See [telemetry/audit_summary.json](telemetry/audit_summary.json).
