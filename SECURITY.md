# SECURITY.md

## Supported Versions

The ASI Master Engine is a proprietary, closed-source generative compiler engineered exclusively for the Ancient Survival Instincts production pipeline. Because this operates as a locked, sovereign simulation environment, there are no public releases, forks, or community patches supported at this time.

| Version | Supported | Status |
| :--- | :---: | :--- |
| **700.x** | ❌ | Internal Production Use Only |
| **< 700.x** | ❌ | Deprecated / Archived |

---

## Advanced Threat Mitigation & Repository Hardening

To protect the deterministic 700-law architecture from supply chain attacks, man-in-the-middle (MITM) payload hijacking, latent space exploits, and unauthorized heuristic tampering, the Ancient Survival Instincts repository operates under absolute Zero-Trust GitHub Advanced Security protocols:

* **Strict Cryptographic Commit Verification (GPG/SSH):** The master branch is mathematically locked. Every commit must be cryptographically signed via verified GPG or SSH keys belonging explicitly to Christopher John Stevens. Unsigned or unverified commits trigger an immediate hardware-level rejection and repository alert.
* **The Fork & Pull Request Quarantine:** Automated merging and community contributions are permanently disabled. Any unauthorized pull request attempting to inject external code, alter API dependencies, or soften the 700-law physics constraints will be automatically incinerated without review.
* **CodeQL Static Application Security Testing (SAST):** Automated architectural code scanning is permanently active at maximum strictness. Every commit is evaluated to identify structural vulnerabilities, memory leak vectors, or logic flaws within the Python compiler before they can impact the render pipeline.
* **Absolute Secret Scanning & Push Protection:** Push protection acts as the final gateway firewall. The repository scans its entire history and actively blocks any commit attempting to push exposed API keys, API authentication tokens, SSH keys, or non-provider generic passwords. Credentials are mathematically prevented from reaching the repository history.
* **Dependency Review & Supply Chain Quarantine:** Upstream API dependencies and third-party Python libraries are treated as actively hostile. Dependency Review serves as a strict security gate, instantly blocking the introduction of libraries with known vulnerabilities, unauthorized data-scraping telemetry, or unwanted open-source licensing.
* **Payload Encryption & API Tunneling:** All generation payloads sent between the local Python compiler and cloud-based latent models must be transmitted via AES-256 encrypted tunnels to prevent prompt-injection hacks or transit interception.

---

## Threat Response: The Omega Failsafe

If the repository's telemetry detects an active brute-force attack, an unauthorized neural weight injection, or a compromised dependency, the system is authorized to execute the Omega Failsafe. This triggers an automatic, immediate revocation of all active API keys, severs the cloud rendering pipeline, and executes a localized core dump to protect the historical asset cache.

---

## Reporting a Vulnerability

If an architectural vulnerability, latent space exploit, or code flaw is identified within the 700-law deterministic framework, do not open a public GitHub issue. 

To prevent unauthorized exploitation of the generative pipeline—specifically regarding model dependencies, VRAM fragmentation leakage, or hardware-level neural overrides—all vulnerability reports, security concerns, or adversarial audit findings must be submitted privately to Christopher John Stevens.

### Protocol for Reporting:
* Do not submit pull requests to patch vulnerabilities.
* Provide a detailed breakdown of the exploit (e.g., bypassing the Metallurgical Quarantine, forcing aesthetic drift, triggering autoencoder bottleneck compression loss).
* Include the specific engine section where the failure occurs.

All private submissions are subjected to a rigorous adversarial audit to ensure the absolute structural integrity of the Ancient Survival Instincts rendering pipeline.

---

## Copyright & Licensing

Copyright © 2026 Chris J. Stevens. All Rights Reserved.

This is a proprietary, closed-source generative compiler. No license is granted for use, modification, distribution, or the creation of derivative works. The code and documentation are hosted publicly strictly for portfolio verification and adversarial audit logging.
