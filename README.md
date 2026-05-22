# Michael Wolf

Computer Science student and Army National Guard Soldier building toward a career in DoD cybersecurity and cleared contractor work. Currently completing a B.S. in Computer Science at WGU while pursuing certifications aligned to the DoD 8140 framework.

Long-term goal: Work in cleared cyber operations.

---

## Technical Focus

| Area | Details |
| --- | --- |
| Languages | Python, C++, Java, Rust, Bash, HTML/CSS/JavaScript |
| Systems | macOS, Linux (Kali, Pop!_OS, Ubuntu) |
| Security Tools | Wazuh, Nmap, Wireshark |
| Platforms | Proxmox VE, Git |
| Concepts | Threat detection, SIEM, AD attack surface analysis, network scanning, file integrity monitoring, virtualization |

---

## Projects

### Cybersecurity

| Project | Description | Stack |
| --- | --- | --- |
| [cloudtrail-anomaly-alerter](https://github.com/mikelobocyber/cloudtrail-anomaly-alerter) | Serverless AWS security tool that monitors CloudTrail logs in real time, detects suspicious API activity across five rule categories, and maps every finding to a MITRE ATT&CK technique. Alerts via SNS email and structured JSON logs for SIEM ingestion. | Python, AWS Lambda, SAM |
| [SniffSnorf](https://github.com/mikelobocyber/SniffSnorf) | Async port scanner with a built-in threat surface analyst. Fingerprints host type, flags dangerous exposures in plain English, and maps every finding to a MITRE ATT&CK technique. | Rust, tokio |
| [Fenrir](https://github.com/mikelobocyber/Fenrir) | CPU-focused password cracker targeting memory-hard hash algorithms: Argon2, bcrypt, and scrypt. Uses rayon for parallel mutation across wordlists with rule-based candidate generation. | Rust, rayon |
| [UCSAT](https://github.com/mikelobocyber/UCSAT-UnitCommunicationsSecurityAssessmentTool-) | CLI tool that walks unit leaders through a 25-question communications security assessment across five weighted categories, scores posture in real time, and saves a report to disk. | Python |
| [File Integrity Monitor](https://github.com/mikelobocyber/file-integrity-monitor) | Monitors directories for unauthorized file changes using SHA-256 cryptographic hashing. Detects additions, deletions, and modifications against a persistent baseline. | Python |
| [Port Scanner](https://github.com/mikelobocyber/port-scanner) | Multithreaded network scanner for detecting open ports and running services across a target range. | Python |
| [Password Strength Checker](https://github.com/mikelobocyber/password-strength-checker) | CLI tool that evaluates password entropy, length, and character composition to score security strength. | Python |

### Software Development

| Project | Description | Stack |
| --- | --- | --- |
| [voice-civics-128](https://github.com/mikelobocyber/voice-civics-128) | Free web app for practicing the 2025 USCIS naturalization civics test by speaking answers out loud. Speech recognition, state-specific answers, and exam simulation mode. Live at [mikelobocyber.github.io/voice-civics-128](https://mikelobocyber.github.io/voice-civics-128/) | HTML, CSS, JavaScript |
| WolfTrack | Fully local iOS calorie tracking app. Scans product barcodes, retrieves nutrition data via the Open Food Facts API, and logs daily intake with no server or account required. | Rust, SwiftUI, SwiftData |
| [Shelf](https://github.com/mikelobocyber/shelf) | Fully local EPUB and PDF reader that runs in the browser or as a desktop app. No server, no uploads, no accounts. Includes bookmarks, reading progress, metadata editing, and optional library folder sync. | JavaScript, CSS, Electron |

---

## Homelab

Proxmox-based cybersecurity homelab running on a dedicated mini PC with LUKS full-disk encryption, used for hands-on blue team skill development and portfolio work.

| Component | Details |
| --- | --- |
| Hypervisor | Proxmox VE (bare-metal) |
| SIEM | Wazuh — log ingestion, custom detection rules, MITRE ATT&CK-mapped alerts |
| Attacker VM | Kali Linux |
| AD Lab | GOAD (Game of Active Directory) — vulnerable multi-domain environment for attack simulation and detection development |
| Self-Hosted Services | Nextcloud |

Current focus: building Wazuh detection rules for Active Directory-based attacks (Kerberoasting, AS-REP roasting, Pass-the-Hash) with full MITRE ATT&CK documentation.

Full documentation: [lobo-homelab](https://github.com/mikelobocyber/lobo-homelab)

---

## Certifications

| Certification | Status |
| --- | --- |
| ISC2 Certified in Cybersecurity (CC) | In Progress |
| Linux Foundations | In Progress |
| ITIL 4 Foundation | Planned |
| CompTIA Security+ | Planned |
| AWS Cloud Practitioner | Planned |
| CompTIA CySA+ | Planned |

Full roadmap aligned to DoD 8140: [cybersecurity-certifications](https://github.com/mikelobocyber/cybersecurity-certifications)

---

## Education

| Degree | Institution | Status |
| --- | --- | --- |
| B.S. Computer Science | Western Governors University | In Progress |
| M.S. Artificial Intelligence and Machine Learning | Western Governors University | Planned |
