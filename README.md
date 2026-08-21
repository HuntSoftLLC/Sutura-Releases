<!-- markdownlint-disable MD013 MD033 MD041 -->

<p align="center">
  <a href="https://sutura.huntsoft.net/">
    <img src="assets/sutura-mark.png" width="136" alt="Sutura application icon">
  </a>
</p>

<h1 align="center">Sutura Releases</h1>

<p align="center">
  Official downloads, release notes, and security guidance for the Sutura HL7 v2 and FHIR desktop toolkit.
</p>

<p align="center">
  <a href="https://github.com/HuntSoftLLC/Sutura-Releases/releases"><img alt="Latest Sutura release" src="https://img.shields.io/github/v/release/HuntSoftLLC/Sutura-Releases?include_prereleases&amp;sort=semver&amp;display_name=tag&amp;label=release&amp;color=0f766e"></a>
  <a href="https://github.com/HuntSoftLLC/Sutura-Releases/releases"><img alt="Total release downloads" src="https://img.shields.io/github/downloads/HuntSoftLLC/Sutura-Releases/total?color=0f766e"></a>
  <img alt="Platforms: Windows 10 and 11, macOS, and Linux" src="https://img.shields.io/badge/platforms-Windows%2010%2F11%20%C2%B7%20macOS%20%C2%B7%20Linux-475569">
  <a href="https://github.com/HuntSoftLLC/Sutura-Releases/security/policy"><img alt="Security policy with private reporting" src="https://img.shields.io/badge/security-private%20reporting-d99b17?logo=github"></a>
</p>

<p align="center">
  <strong><a href="https://sutura.huntsoft.net/?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=sutura_releases">Visit the official Sutura website</a></strong>
  &nbsp;·&nbsp;
  <a href="https://github.com/HuntSoftLLC/Sutura-Releases/releases">Browse releases</a>
  &nbsp;·&nbsp;
  <a href="SECURITY.md">Security policy</a>
</p>

---

## Download Sutura

Use the [GitHub Releases page](https://github.com/HuntSoftLLC/Sutura-Releases/releases) as the authoritative public
source for Sutura packages and release notes.

1. Open the newest release appropriate for your use of prerelease or stable software.
2. Choose the **Reader** or **Professional** package for your operating system and architecture.
3. Download both the package and its adjacent `.sha256` file.
4. Compare the package's SHA-256 hash before running it.
5. Read the release notes and the packaged `RELEASE-STATUS.txt` before relying on platform or signing claims.

On PowerShell, compare the two displayed hashes:

```powershell
Get-FileHash .\Sutura-Reader-<version>-win-x64.zip -Algorithm SHA256
Get-Content .\Sutura-Reader-<version>-win-x64.zip.sha256
```

Do not disable operating-system security controls merely to launch an unsigned prerelease.

## Choose an edition

| Edition | Intended use | Package boundary |
| --- | --- | --- |
| **Reader** | Free, focused document review | Up to two read-only tabs, basic local HL7 v2 syntax/envelope validation, find/copy, and exact-byte save |
| **Professional** | Licensed interoperability investigation and testing | Full desktop workbench and gated CLI for deeper HL7 v2 and FHIR inspection, validation, editing where supported, comparison, redaction, conversion, and deliberate transport testing |

See the [current edition comparison](https://sutura.huntsoft.net/?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=sutura_releases_readme#editions)
for the maintained feature and licensing summary.

## Platform and release status

| Platform | Current status |
| --- | --- |
| **Windows 11 x64** | Primary qualification target for Sutura 1.0 |
| **Windows 10 22H2 x64** | Compatibility evaluation pending; not yet a supported-platform claim |
| **Linux x64** | Unsigned, experimental, and untested until physical-machine qualification is recorded |
| **macOS x64 and arm64** | Unsigned, experimental, and untested until physical-machine qualification is recorded |

- An explicitly labeled release candidate may contain unsigned Windows portable packages while verified code-signing
  setup is completed. Stable Windows publication requires verified executable and installer signatures.
- The release notes, package manifest, checksum, and `RELEASE-STATUS.txt` are authoritative for a particular artifact.

## About Sutura

Sutura is a local-first desktop toolkit from HuntSoft LLC for reading, inspecting, validating, comparing, and testing
HL7 v2 and FHIR R4, R4B, and R5 documents. Reader keeps basic review available without charge; Professional supports
the deeper workbench and command-line workflows.

Sutura is not a medical device, clinical decision system, production interface engine, or unattended delivery service.
Use synthetic or properly de-identified healthcare data and independently review every result before use.

## Security and support

- Review the repository's [security policy](SECURITY.md).
- Report suspected vulnerabilities through
  [GitHub private vulnerability reporting](https://github.com/HuntSoftLLC/Sutura-Releases/security/advisories/new), not
  through a public issue.
- For Professional licensing and support questions, contact
  [support@huntsoft.net](mailto:support@huntsoft.net?subject=Sutura%20support).

Release packages include the applicable Sutura license, third-party notices, dependency evidence, and an SPDX software
bill of materials. Review those files before distribution or organizational deployment.

## Official links

- [Sutura product website](https://sutura.huntsoft.net/)
- [Reader and Professional comparison](https://sutura.huntsoft.net/?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=sutura_releases_links#editions)
- [Downloads and release notes](https://github.com/HuntSoftLLC/Sutura-Releases/releases)
- [Security policy](https://github.com/HuntSoftLLC/Sutura-Releases/security/policy)

---

Sutura is not affiliated with, sponsored by, or endorsed by Health Level Seven International. HL7 and FHIR are
registered trademarks of Health Level Seven International.
