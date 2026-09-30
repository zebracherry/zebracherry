## ZCherry

Security researcher — web application testing and open-source vulnerability research.
I build offensive security tooling and publish it.

Write-ups at **[noob2root.com](https://noob2root.com)**.

---

### Tooling

| Project | What it does | Stack |
|---|---|---|
| **[ZScan](https://github.com/zebracherry/ZScan)** | Single-file network scanner with 58 embedded NSE-equivalent scripts. Air-gap safe, zero installs. | Python · PowerShell |
| **[RHELGuard](https://github.com/zebracherry/RHELGuard)** | RHEL security audit against CIS Benchmarks and DISA STIG, plus air-gap isolation checks. | Bash · Python |
| **[RustRecon](https://github.com/zebracherry/Rustrecon)** | OSCP-focused async recon framework — classifies a target, then runs only the relevant tool chain. | Rust |
| **[ADReaper](https://github.com/zebracherry/ADReaper)** | Active Directory and Windows privilege-escalation recon over LDAP. Enumeration only, no exploitation. | Python |

### Labs and practice targets

| Project | What it does | Stack |
|---|---|---|
| **[PurpleForest](https://github.com/zebracherry/PurpleForest)** | An Active Directory purple-team lab that detects the attacks run against it and records them. | PowerShell · Ansible |
| **[VaultPay](https://github.com/zebracherry/VaultPay)** | Intentionally vulnerable Android wallet — every OWASP Mobile Top 10 (2024) risk, mapped to MASVS v2.1.0. | Kotlin |
| **[VaultPay-iOS](https://github.com/zebracherry/VaultPay-IOS)** | The iOS counterpart, same coverage using iOS-native insecure primitives. | Swift |

---

All projects are MIT licensed.

The VaultPay apps are **deliberately insecure** — read the `NOTICE` before building, and run
them only on an emulator, simulator or a dedicated test device.

> For authorised security testing only. Only test systems you own or have explicit written
> permission to assess.
