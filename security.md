# Security Practices

## Overview
At Canonical Labs, Inc., we take security seriously and follow industry best practices to ensure the confidentiality, integrity, and availability of our systems and data. This document outlines our core security principles and measures.

---

## **🔐 Data Protection & Encryption**
- **Full-disk encryption**: All employee devices are secured using **FileVault (macOS) or BitLocker (Windows)**.
- **Data in transit**: All communications are encrypted using **TLS 1.2+**.
- **Data at rest**: Sensitive data is encrypted using **AES-256 encryption**.
- **Cloud storage**: We store data in **AWS S3 with server-side encryption (SSE-S3)**.

---

## **🔑 Access Control & Authentication**
- **Least privilege access**: Employees are granted the **minimum access necessary**.
- **Multi-Factor Authentication (MFA)**: Enforced for **AWS, GitHub, Google Workspace, and internal tools**.
- **SSO (Single Sign-On)**: Required for access to critical services.
- **Role-Based Access Control (RBAC)**: Applied to all production systems.

---

## **🛡️ Network Security**
- **VPC Segmentation**: Our production and staging environments are isolated.
- **Security Groups & Firewalls**: We follow the **deny-by-default** principle.
- **Intrusion Detection (IDS)**: AWS **GuardDuty** monitors for suspicious activity.
- **Endpoint Security**: All employee devices run **CrowdStrike Falcon** for endpoint protection.

---

## **🔄 Vulnerability Management**
- **Automated patching**: We use **AWS Patch Manager** to enforce security updates.
- **CVE Scanning**: We continuously monitor for vulnerabilities via **AWS Security Hub & Amazon Inspector**.
- **Penetration Testing**: Conducted at least annually.

---

## **📜 Compliance & SOC 2 Readiness**
- **SOC 2 Type II**: Actively working toward full compliance.
- **Security Awareness Training**: All employees undergo annual security training.
- **Incident Response Plan**: We have a well-defined **IRP** that includes **detection, response, and recovery procedures**.

---

## **📝 Contact & Reporting Security Issues**
We encourage responsible disclosure of security vulnerabilities. If you have any concerns, please reach out to our security team at **security@gocanonical.com**.

