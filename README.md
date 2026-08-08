<div align="center">

<img src="./assets/ChellTools.png" width="110" alt="ChellSpace Logo" />

# CHELL NEXUS
### Master Command Center & Ecosystem Administration Console
**Author: Marchell Adi Pratama • ChellSpace Security Labs**

[![Downloads](https://img.shields.io/github/downloads/MarchellProGit/ChellNexus/total?style=for-the-badge&color=00F0FF&logo=github&logoColor=white)](https://github.com/MarchellProGit/ChellNexus/releases)
[![Visitors](https://komarev.com/ghpvc/?username=MarchellProGit-ChellNexus&color=0080FF&style=for-the-badge&label=VISITORS)](https://github.com/MarchellProGit/ChellNexus)
[![Repo Size](https://img.shields.io/github/repo-size/MarchellProGit/ChellNexus?style=for-the-badge&color=38BDF8)](https://github.com/MarchellProGit/ChellNexus)
[![Build](https://img.shields.io/badge/Build-v1.0.0--PROD-00ff41?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/MarchellProGit/ChellNexus/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11_x64-38BDF8?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/MarchellProGit/ChellNexus/releases)
[![License](https://img.shields.io/badge/License-Proprietary_EULA-A855F7?style=for-the-badge&logo=shield&logoColor=white)](#terms-of-service--license)
[![Integrity](https://img.shields.io/badge/Security-SHA256_Verified-10B981?style=for-the-badge&logo=security&logoColor=white)](#security--integrity)

---

</div>

## Executive Summary

ChellNexus is the centralized administration command center for the ChellSpace Ecosystem. Engineered exclusively for ecosystem administrators and security leads, ChellNexus provides real-time hardware fingerprint (HWID) authorization management, client access tier control, telemetry audit inspection, and instant credential revocation capabilities.

Built with a custom dark-mode desktop GUI and encrypted communication protocols, ChellNexus serves as a dedicated security diagnostic module within the ChellSpace desktop security ecosystem.

---

## Authentication & Access Protocol

> **System Administration Scope**: ChellNexus is a restricted administrative console reserved exclusively for ecosystem owners and system administrators.

### Administrative Access Workflow
1. **Master Authentication**: System administrators launch `ChellNexus_ChellSpace.exe` on authorized management hardware.
2. **Cloud Telemetry Audit**: ChellNexus connects directly to the cloud infrastructure to manage user license records and active tool entries (`tools_registry`).
3. **HWID Access Control**: Administrators grant, revoke, or modify hardware access permissions across all registered desktop modules.
4. **Global System Inspector**: Live monitoring of active client workstation telemetry, geographic connections, and execution logs.

---

## Technical Specifications

| Core Attribute | Implementation Details | Security / Rating |
| :--- | :--- | :---: |
| **HWID Fingerprinting** | WMI multi-factor hardware hashing (CPU, Motherboard, BIOS UUID) | Critical |
| **Cloud Synchronization** | Bidirectional state synchronization via Supabase REST API & Realtime | High |
| **Payload Encryption** | AES-256 CBC encryption for authorization tokens & session states | Critical |
| **License Audit Engine** | Automatic timestamp audit with automated access tier enforcement | High |
| **Telemetry Aggregator** | Real-time terminal output with IP geolocation and host hardware telemetry | Standard |

---


## Key Features

- **[ ✦ ] Ecosystem Administration**: Centralized command center for managing all ChellSpace modules.
- **[ ✦ ] HWID Access Control**: Real-time hardware fingerprint validation and authorization management.
- **[ ✦ ] Client Telemetry Audit**: Live monitoring of active client connections, execution logs, and network telemetry.
- **[ ✦ ] Credential Revocation**: Instant revocation of access licenses and immediate module termination for compromised hosts.
- **[ ✦ ] Secure Cloud Sync**: Encrypted bidirectional state synchronization via Supabase backend.

---
## System Architecture

```
+----------------------+      +----------------------+      +------------------------+
| Administrator Console | ---> | HWID Fingerprint    | ---> | Cloud Database       |
| (ChellNexus.exe)     |      | SHA-256 Hash Engine |      | Authorization Rules |
+----------------------+      +----------------------+      +------------------------+
                                                                        |
                                                                        v
                                                            +------------------------+
                                                            | Master Access Panel    |
                                                            +------------------------+
```

---

## System Requirements

| Resource | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 x64 (Build 19041+) | Windows 11 x64 (Latest Build) |
| **Processor** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 |
| **System Memory** | 4 GB RAM | 8 GB RAM or higher |
| **Network Infrastructure** | Active Internet Connection | High-Speed Broadband / Low Latency |
| **Runtime Binaries** | Standalone Executable | Standalone Executable |

---

## Binary Release Distribution

The official compiled executable binary is distributed exclusively via GitHub Releases:

- **Official Release Download**: [ChellNexus_ChellSpace.exe (v1.0.0-PROD)](https://github.com/MarchellProGit/ChellNexus/releases/tag/v1.0.0)

---

## Security & Integrity Verification

To ensure that your downloaded binary has not been modified or corrupted during transit, verify its cryptographic hash against the official digest:

```text
File Name : ChellNexus_ChellSpace.exe
Algorithm : SHA-256
Checksum  : 41ad785e0a649fb92676d4087c13552c2430f55b966f783065197c5940000000
Status    : Verified Clean (ChellSpace Security Labs)
```

---

## Terms of Service & License

Copyright (C) 2026 Marchell Adi Pratama • ChellSpace Ecosystem. All Rights Reserved.

This software binary is distributed under a strict Proprietary End-User License Agreement (EULA):
- Reverse engineering, decompilation, dynamic analysis patching, or redistribution of compiled binaries is strictly prohibited.
- Distributed exclusively for authorized system administration, security auditing, and educational research purposes.

---

<div align="center">
  <sub>Developed by <strong>Marchell Adi Pratama</strong> • ChellSpace Ecosystem</sub>
</div>
