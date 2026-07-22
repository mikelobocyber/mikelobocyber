# Michael Wolf Scherwitz

**Computer Science Graduate | Army National Guard Soldier | Cybersecurity-Focused Software Developer**

I am a Computer Science graduate building toward a career in defensive cybersecurity, DoD-adjacent IT, security operations, and secure software development. My work focuses on practical security tooling, automation, log analysis, SIEM detection, systems programming, and hands-on blue team labs.

This GitHub documents projects that show how I build, test, explain, and improve technical systems. My current focus is strengthening my cybersecurity foundation through Security+, authorized web security practice, homelab-based detection engineering, and practical software projects that support IT and security workflows.

---

## Core Focus Areas

- Defensive cybersecurity tooling and automation
- SIEM detection engineering and log analysis
- Cloud security monitoring and alerting
- Network scanning and threat surface assessment
- Web application security practice and OWASP Top 10
- Python, Java, Rust, and systems-oriented development
- Linux, virtualization, and homelab infrastructure
- Software design, testing, documentation, and maintainability

---

## Technical Skills

| Area | Tools & Technologies |
| --- | --- |
| Languages | Python, Java, C++, Rust, Bash, SQL, HTML, CSS, JavaScript |
| Security | Wazuh, MITRE ATT&CK, Nmap, Wireshark, file integrity monitoring, CloudTrail analysis, OWASP Top 10, authorized web security testing |
| Systems | Linux, Kali Linux, Ubuntu, macOS, Proxmox VE, VMs/LXC, Docker fundamentals |
| Cloud & Platforms | AWS Lambda, AWS SAM, SNS, CloudTrail, GitHub Pages, Electron |
| Data & ML | scikit-learn, pandas, numpy, model evaluation, cross-validation, regression, classification, feature engineering |
| Development | Git, GitHub, REST APIs, Spring Boot, JPA, MySQL, command-line tooling, testing, debugging, documentation |
| Computer Science | Data structures, algorithms, object-oriented programming, databases, operating systems, software engineering, quality assurance |

---

## Featured Projects

### Machine Learning Log Anomaly Detection — SOC Alert Triage Tool

A cybersecurity-focused machine learning project that classifies HDFS log sequences as normal or anomalous to support SOC alert triage.

- Built a Python/scikit-learn ML pipeline for log anomaly detection.
- Compared Logistic Regression, Random Forest, and Gradient Boosting across 575,061 records and 31 features.
- Selected Random Forest after reaching 0.9988 anomalous-class F1 on held-out test data.
- Validated performance with five-fold cross-validation, reaching 0.9981 mean F1.
- Built a CLI prediction tool that loads saved model artifacts and returns a predicted label with a confidence score.
- Documented system architecture, preprocessing, evaluation, risks, monitoring, and future REST API integration.

**Stack:** Python, scikit-learn, pandas, numpy, joblib, CLI tooling

---

### CloudTrail Anomaly Alerter

Serverless AWS security monitoring tool for identifying suspicious CloudTrail activity and sending email alerts.

- Monitors CloudTrail-style events for risky API activity.
- Maps findings to MITRE ATT&CK concepts.
- Sends notifications through SNS.
- Designed as a lightweight cloud security automation project that can be deployed with AWS SAM.

**Stack:** Python, AWS Lambda, AWS SAM, Amazon SNS, CloudTrail

---

### Travel Booking Back-End — Spring Boot REST API

A Java/Spring Boot back end for a travel booking application using an existing Angular front end and MySQL database.

- Built REST API functionality for checkout and order placement.
- Implemented JPA/MySQL persistence with entity, DAO/repository, service, and controller layers.
- Added validation for front-end input requirements.
- Implemented service-layer checkout logic and transactional order handling.
- Seeded sample customer data and verified successful order creation through the integrated app.

**Stack:** Java, Spring Boot, Spring Data JPA, REST, MySQL, Lombok

---

### WGUPS Routing & Package Status Simulator

A Python routing simulation for package delivery with custom data structures, constraints, and time-based status reporting.

- Built a custom hash table with chaining for package storage and lookup.
- Implemented a two-pass nearest-neighbor routing heuristic for deadline-sensitive deliveries.
- Modeled 40 packages across three trucks with capacity limits, deadlines, delayed packages, truck restrictions, and a wrong-address correction.
- Added CSV data ingestion, address normalization, mileage tracking, and an interactive status interface.
- Completed all deliveries under the required mileage limit.

**Stack:** Python, custom data structures, CSV parsing, algorithmic routing

---

### AI Model Optimization — Air Quality Health Risk Prediction

An AI/ML optimization project focused on improving prediction accuracy for urban air quality and health risk scoring.

- Tuned Random Forest regression models using RandomizedSearchCV and five-fold cross-validation.
- Built and compared ensemble approaches including VotingRegressor and BaggingRegressor.
- Improved RMSE from 0.1858 to 0.1131, lowering prediction error by about 39.1%.
- Improved test R² from 0.9220 to 0.9711.
- Documented model limitations, cross-validation variance, feature importance, and generalization concerns.

**Stack:** Python, scikit-learn, pandas, ensemble learning, model evaluation

---

### Security CLI Tooling

A set of small security-focused command-line tools built to practice practical defensive and systems programming skills.

| Project | Description | Stack |
| --- | --- | --- |
| [SniffSnorf](https://github.com/mikelobocyber/SniffSnorf) | Async port scanner with a built-in threat surface analyst. Identifies exposed services, explains risk in plain English, and maps findings to MITRE ATT&CK techniques. | Rust, tokio |
| [File Integrity Monitor](https://github.com/mikelobocyber/file-integrity-monitor) | Detects unauthorized file additions, deletions, and modifications using SHA-256 hashing and a persistent baseline. | Python |
| [Port Scanner](https://github.com/mikelobocyber/port-scanner) | Multithreaded scanner for identifying open ports and exposed services across a target range. | Python |
| [Password Strength Checker](https://github.com/mikelobocyber/password-strength-checker) | CLI utility that evaluates password strength using length, composition, and entropy-based scoring. | Python |
| [Fenrir](https://github.com/mikelobocyber/Fenrir) | Local password-auditing lab tool for studying memory-hard hash algorithms, parallel processing, and rule-based candidate generation in controlled environments. | Rust, rayon |

---

## Homelab

I maintain a Proxmox-based cybersecurity homelab on a dedicated mini PC with LUKS full-disk encryption. The lab is used for blue team practice, detection engineering, Linux administration, and controlled attack simulation.

| Component | Details |
| --- | --- |
| Hypervisor | Proxmox VE on bare metal |
| SIEM | Wazuh for log ingestion, custom rules, and MITRE ATT&CK-mapped alerts |
| Attacker VM | Kali Linux |
| Active Directory Lab | GOAD — vulnerable multi-domain environment for attack simulation and detection development |
| Self-Hosted Services | Nextcloud |

Current focus:

- Writing and testing Wazuh detection rules for Active Directory-based attacks.
- Practicing detection logic for Kerberoasting, AS-REP roasting, Pass-the-Hash, suspicious PowerShell, and authentication anomalies.
- Documenting detection steps, expected logs, false-positive considerations, and response notes.

Full documentation: [lobo-homelab](https://github.com/mikelobocyber/lobo-homelab)

---

## Authorized Web Security Practice

I am building web application security skills through authorized labs and responsible testing only.

Current focus:

- OWASP Top 10 fundamentals
- PortSwigger Web Security Academy labs
- Vulnerability validation and remediation notes
- Responsible disclosure workflow
- Clear vulnerability writeups written for technical and non-technical readers

I do not test systems without authorization.

---

## Additional Software Projects

| Project | Description | Stack |
| --- | --- | --- |
| [voice-civics-128](https://github.com/mikelobocyber/voice-civics-128) | Free web app for practicing the 2025 USCIS naturalization civics test by speaking answers out loud. Includes speech recognition, state-specific answers, and exam simulation mode. | HTML, CSS, JavaScript |
| WolfTrack | Local-first nutrition and calorie tracking app concept with barcode scanning and nutrition lookup. | SwiftUI, SwiftData, Open Food Facts API |
| [Shelf](https://github.com/mikelobocyber/shelf) | Local-first EPUB/PDF reader for browser or desktop use with bookmarks, reading progress, metadata editing, and optional library sync. | JavaScript, CSS, Electron |
| [UCSAT](https://github.com/mikelobocyber/UCSAT-UnitCommunicationsSecurityAssessmentTool-) | CLI assessment tool that helps unit leaders evaluate communications security across weighted categories and generate a local report. | Python |

---

## Certifications

| Certification | Issuer | Status |
| --- | --- | --- |
| ITIL 4 Foundation | PeopleCert | Complete |
| LPI Linux Essentials | Linux Professional Institute | Complete |
| Google Data Analytics Certificate | Google | Complete |
| CompTIA Security+ | CompTIA | In Progress |
| AWS Cloud Practitioner | Amazon Web Services | Planned |
| CompTIA CySA+ | CompTIA | Planned |

Full roadmap aligned to DoD 8140-oriented career goals: [cybersecurity-certifications](https://github.com/mikelobocyber/cybersecurity-certifications)

---

## Education

| Degree / Area | Status |
| --- | --- |
| B.S. Computer Science | Complete |
| Artificial Intelligence and Machine Learning | Planned graduate study |

---

## Military

| Organization | Status |
| --- | --- |
| Army National Guard | Drilling with Recruit Sustainment Program while awaiting BCT/AIT |
| Security Clearance | Secret clearance process initiated; interview completed; final eligibility pending |

---

## Languages

| Language | Proficiency |
| --- | --- |
| English | Native fluency |
| Spanish | Native / professional fluency |
| Catalan | Professional fluency |
| French | Conversational |
| Italian | Conversational |

---

## Career Direction

My goal is to grow into defensive cybersecurity, cyber operations, security engineering, or technical support roles supporting government, DoD-adjacent, and security-focused environments.

I am especially interested in practical blue team work:

- Detection logic
- Log analysis
- SIEM tuning
- Cloud security monitoring
- Secure software development
- Automation that makes security work easier to understand and act on

---

## Contact

- GitHub: [github.com/mikelobocyber](https://github.com/mikelobocyber)
- Location: Yukon, Oklahoma

