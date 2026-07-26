<div align="center">

<img src="./assets/ChellTools.png" width="110" alt="ChellSpace Logo" />

# CHELL NEXUS
### Central Hardware Licensing & Security Management Command Center
**Author: Marchell Adi Pratama • ChellSpace Security Labs**

[![Build](https://img.shields.io/badge/Build-v1.0.0--PROD-00ff41?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/MarchellProGit/ChellNexus/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11_x64-38BDF8?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/MarchellProGit/ChellNexus/releases)
[![License](https://img.shields.io/badge/License-Proprietary_EULA-A855F7?style=for-the-badge&logo=shield&logoColor=white)](#terms-of-service--license)
[![Integrity](https://img.shields.io/badge/Security-SHA256_Verified-10B981?style=for-the-badge&logo=security&logoColor=white)](#security--integrity)

---

</div>

## Executive Summary

ChellNexus is the enterprise-grade central administration command center for the ChellSpace Ecosystem. Engineered for high-throughput software license management, hardware fingerprint (HWID) binding, and real-time database synchronization, ChellNexus empowers administrators to control client access tiers, inspect system audit logs, and revoke unauthorized software redistributions instantly.

Built with a custom dark-mode GUI and encrypted communication protocols, ChellNexus serves as the backbone of the ChellSpace desktop security architecture.

---

## Technical Specifications

| Component | Specification | Security Rating |
| :--- | :--- | :---: |
| **HWID Fingerprinting** | WMI-based multi-factor hardware hashing (CPU, Motherboard, BIOS UUID) | Critical |
| **Database Telemetry** | Bidirectional state synchronization via Supabase REST API & Realtime Channels | High |
| **Payload Packaging** | AES-256 CBC encryption for authorization tokens | Military-Grade |
| **License Audit Engine** | Automatic timestamp audit with automated access tier downgrades | High |
| **Telemetry Aggregator** | Real-time terminal output with IP geolocation and host hardware telemetry | Standard |

---

## System Architecture

```
+----------------------+      +----------------------+      +------------------------+
| Client Workstation   | ---> | HWID Fingerprint     | ---> | Supabase Cloud Database|
| (ChellNexus.exe)     |      | SHA-256 Hash Engine  |      | Authorized Tokens      |
+----------------------+      +----------------------+      +------------------------+
                                                                        |
                                                                        v
                                                            +------------------------+
                                                            | Unlock Master Console  |
                                                            +------------------------+
```

---

## System Requirements

- **Operating System**: Windows 10 / Windows 11 (64-bit Edition)
- **Processor**: Dual-Core x64 2.0 GHz or higher
- **Memory**: Minimum 4 GB RAM
- **Network**: Active broadband connection for licensing telemetry
- **Runtime**: Self-contained standalone executable binary

---

## Binary Release Distribution

The official compiled executable is available exclusively on the GitHub Releases page:

- **Download**: [ChellNexus_ChellSpace.exe (v1.0.0-PROD)](https://github.com/MarchellProGit/ChellNexus/releases/tag/v1.0.0)

---

## Security & Integrity

To verify that your downloaded binary has not been tampered with, compare the SHA-256 checksum of `ChellNexus_ChellSpace.exe`:

```text
File Name : ChellNexus_ChellSpace.exe
SHA-256   : 41ad785e0a649fb92676d4087c13552c2430f55b966f783065197c5940000000
Status    : Verified Clean (ChellSpace Security Labs)
```

---

## Terms of Service & License

Copyright (C) 2026 Marchell Adi Pratama • ChellSpace Ecosystem. All Rights Reserved.

This software binary is distributed under a strict Proprietary End-User License Agreement (EULA):
- Unauthorized reverse engineering, decompilation, or redistribution is strictly prohibited.
- Provided exclusively for authorized system administration and educational diagnostic research.

---

<div align="center">
  <sub>Developed by <strong>Marchell Adi Pratama</strong> • ChellSpace Ecosystem</sub>
</div>
