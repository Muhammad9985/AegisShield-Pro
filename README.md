<p align="center">
  <img src="icons/icon128.png" alt="AegisShield Pro Logo" width="100" height="100" style="filter: drop-shadow(0 0 20px rgba(0, 240, 255, 0.4));" />
</p>

<h1 align="center">🛡️ AEGISSHIELD PRO</h1>

<p align="center">
  <strong>Enterprise Defensive Web Security Operations Center (SOC) & Automated Remediation Platform</strong><br>
  <em>Built for Google Chrome • Manifest V3 • Zero External Telemetry • 100% Client-Side Privacy</em>
</p>

<p align="center">
  <a href="#-key-features"><img src="https://img.shields.io/badge/Modules-25%20Enterprise%20Engines-00f0ff?style=for-the-badge&logo=shield" alt="25 Modules"></a>
  <a href="#-dual-perspective-mode"><img src="https://img.shields.io/badge/Perspective-Red%20Hat%20%7C%20White%20Hat-ff0055?style=for-the-badge&logo=target" alt="Dual Perspective"></a>
  <a href="#-regulatory-compliance"><img src="https://img.shields.io/badge/Compliance-OWASP%20%E2%80%A2%20NIST%20%E2%80%A2%20PCI--DSS-7928ca?style=for-the-badge&logo=lock" alt="Compliance"></a>
  <a href="https://developer.chrome.com/docs/extensions/mv3/intro/"><img src="https://img.shields.io/badge/Chrome-Manifest%20V3-4285f4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Manifest V3"></a>
  <a href="https://mr-software.online/"><img src="https://img.shields.io/badge/Author-Muhammad%20Rafique-00dfa2?style=for-the-badge&logo=safari" alt="Author"></a>
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-key-features">Key Features</a> •
  <a href="#-the-25-security-modules">25 Modules</a> •
  <a href="#-dual-perspective-mode">Red Hat vs White Hat</a> •
  <a href="#-remediation--hardening-suite">Hardening Center</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-author--connect">Author</a>
</p>

---

## 🌐 Overview

**AegisShield Pro** transforms Google Chrome into an elite, browser-native **Defensive Web Security Operations Center (SOC)**. Designed for Principal Cybersecurity Engineers, Penetration Testers, DevSecOps teams, and Web Architects, AegisShield Pro audits live web applications across **25 distinct attack vectors in real-time**—with zero latency, zero cloud dependency, and total confidentiality.

From deep cryptographic transport inspections (HSTS, TLS, CSP, CORS) to proactive secrets discovery (AWS, Stripe, OpenAI, Claude, JWT), client-side DOM XSS sinks, known library CVE correlations, and DNS OSINT posture checks, AegisShield Pro delivers comprehensive, actionable intelligence right in your browser.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                           AEGISSHIELD PRO SOC CORE                          │
├──────────────────────────────────────┬──────────────────────────────────────┤
│       🔴 RED HAT PERSPECTIVE         │       ⚪ WHITE HAT PERSPECTIVE        │
│   Adversarial Recon & Attack Surface │    Defensive Posture & Hardening     │
├──────────────────────────────────────┼──────────────────────────────────────┤
│ • MITRE ATT&CK TTP Matrix Mapping    │ • Zero-Trust Strict CSP Synthesizer  │
│ • Reproducible cURL Replay Snippets  │ • Multi-Server Config Generators     │
│ • Burp Suite & OWASP ZAP Scope Export│ • NIST, PCI-DSS, ISO 27001 Crosswalk │
│ • Attack Surface & Asset Footprint   │ • Automated C-Suite Executive Briefs │
└──────────────────────────────────────┴──────────────────────────────────────┘
```

---

## ✨ Key Capabilities at a Glance

- **🎯 25 Autonomous Security Engines**: Scans headers, transport encryption, cookies, storage, secrets, DOM sinks, cloud buckets, and CVEs simultaneously.
- **🔄 Dual Perspective Architecture**: Seamlessly pivot between an **Adversary Threat Model (Red Hat)** and an **Enterprise Defensive Remediation Center (White Hat)**.
- **🛡️ MITRE ATT&CK® Enterprise Mapping**: Automatically correlates every discovered vulnerability with relevant MITRE ATT&CK tactics, techniques, and sub-techniques.
- **⚡ Instant Verification with cURL**: Every finding generates an instant, copy-pasteable cURL command with custom headers, user-agents, and inspection flags.
- **🔒 Dynamic Strict CSP Synthesizer**: Parses detected scripts, styles, CDNs, and domains to synthesize a production-hardened `Content-Security-Policy` with a single click.
- **🚀 9 Multi-Server Hardening Generators**: Generates production-ready configurations for Nginx, Apache, Caddy, Cloudflare Rules, AWS WAF, Next.js, Node/Express, Docker, and GitHub Actions DevSecOps.
- **📊 4 Standalone Enterprise Reports**:
  1. **Executive Summary Report (HTML)**: C-Suite visual scorecards, risk radar, and compliance indices.
  2. **Technical Pen-Test Audit (HTML)**: Full finding breakdown, CWEs, remediation steps, and verification payloads.
  3. **Burp Suite & OWASP ZAP Target Scope**: JSON scope definitions ready to import directly into enterprise intercepting proxies.
  4. **Raw Telemetry JSON Log**: Machine-readable JSON data for SIEM/SOC ingestion.
- **🔐 100% Local & Air-Gapped Safe**: Runs entirely within your Chrome runtime. No user credentials, cookies, tokens, or scanned URLs are ever transmitted to third-party servers.

---

## 🛡️ The 25 Security Modules

AegisShield Pro delivers exhaustive coverage across modern web application threat vectors:

| # | Module | Category | Description |
|:---:|:---|:---:|:---|
| `01` | **Dynamic Security Score** | Scoring & Health | Computes a real-time 0–100 cyber posture score, grading from **A+ to F** with risk-weighted deductions. |
| `02` | **Attack Surface Discovery** | Reconnaissance | Identifies all external origins, CDNs, trackers, analytics, cloud storage, and SaaS endpoints. |
| `03` | **TLS / HTTPS Transport Health** | Cryptography | Validates TLS transport, protocol version, certificate pinning, HSTS enforcement, and plaintext fallbacks. |
| `04` | **HTTP Security Headers** | Defensive Headers | Deep analysis of CSP, HSTS, X-Frame-Options, X-Content-Type-Options, Referrer-Policy, and COOP/CORP. |
| `05` | **Cookie Security & Privacy** | Session Armor | Audits every cookie for `Secure`, `HttpOnly`, `SameSite` flags, and wildcard domain scoping with automatic value masking. |
| `06` | **Authentication Security** | Identity & Access | Analyzes login forms, HTTPS submission targets, password field autocomplete behaviors, and MFA hints. |
| `07` | **Client Storage & Session Leakage** | Client-Side Storage | Inspects `localStorage` and `sessionStorage` for exposed JWTs, bearer tokens, and session fixation risks. |
| `08` | **Exposed Internal Ports & Services** | Port Reconnaissance | Scans client bundles for hardcoded dev/management ports (`3000`, `8080`, `8443`, `9200`, `27017`). |
| `09` | **Information Disclosure & Banners** | Fingerprinting | Detects exposed server banners, stack traces, debug overlays, and sensitive developer comments. |
| `10` | **CMS & Framework Detection** | Fingerprinting | Identifies CMS engines (WordPress, Shopify, Drupal) and UI frameworks (React, Vue, Angular, Next.js). |
| `11` | **Dependency Risk & Known CVEs** | Supply Chain | Cross-references loaded client libraries (jQuery, Lodash, Axios, Bootstrap, Moment) against known CVE databases. |
| `12` | **Endpoint & API Surface Mapper** | API Recon | Extracts and catalogs REST endpoints, GraphQL queries, form actions, and AJAX targets. |
| `13` | **Client-Side DOM XSS Injections** | Injection Defense | Audits source code for dangerous JavaScript sinks (`innerHTML`, `document.write`, `eval`, `Function`, `postMessage('*')`). |
| `14` | **OWASP Top 10 (2021) Mapping** | Compliance | Groups and indexes all identified vulnerabilities against official OWASP Top 10 categories (A01–A10). |
| `15` | **API Security & Documentation** | API Governance | Audits exposed Swagger/OpenAPI docs, GraphQL playground interfaces, and missing API auth guards. |
| `16` | **Public Cloud Bucket Exposures** | Cloud Misconfig | Scans for public AWS S3 buckets, Google Cloud Storage, Firebase Realtime Databases, and Azure Blobs. |
| `17` | **Sensitive File & Backup Scanner** | Reconnaissance | Checks for exposed references to `.env`, `.git/config`, `database.sql`, `backup.tar.gz`, and `phpinfo.php`. |
| `18` | **Secrets & Token Scanner** | Secret Protection | Scans for 15+ API key patterns (AWS, Stripe, OpenAI, Claude, GitHub PAT, Slack Webhooks, DB credentials). |
| `19` | **Open Redirect Security** | Navigation Safety | Analyzes query parameters for unvalidated redirect parameters (`?redirect=`, `?url=`, `?next=`, `?dest=`). |
| `20` | **CORS Configuration Audit** | Cross-Origin Policy | Evaluates `Access-Control-Allow-Origin` and flags insecure wildcard origins paired with `Allow-Credentials: true`. |
| `21` | **Bot Mitigation & Anti-Abuse** | Anti-Bot Defense | Detects bot defense systems: Cloudflare Turnstile, Google reCAPTCHA, hCaptcha, and WAF rate-limiting headers. |
| `22` | **Historical Timeline & Drift** | Threat Monitoring | Stores audit snapshots in local storage to track security score drift and identify newly introduced vulnerabilities. |
| `23` | **Continuous Monitoring Alerts** | Live Telemetry | Employs Chrome background service workers to notify engineers if a critical vulnerability or score drop occurs. |
| `24` | **Executive & Technical Reporting** | Enterprise Export | Generates branded C-Suite Executive Summary HTML, Technical Pen-Test HTML, and raw JSON telemetry files. |
| `25` | **SOC Fix Center & Code Synthesizer** | Automated Remediation| Dynamic code synthesis engine providing copy-paste hardening recipes across 9 web servers and WAFs. |

---

## 🔴 Dual Perspective Mode

Switch between operational perspectives with one click:

### 🔴 Red Hat (Adversarial / Offensive)
- **MITRE ATT&CK® TTP Matrix**: Visualizes active threat techniques (e.g. *T1059.007 JavaScript Execution*, *T1190 Exploit Public-Facing Application*, *T1552 Unsecured Credentials*).
- **Automated Verification cURL**: Instant command-line replay strings that replicate the exact test request to verify the vulnerability off-browser.
- **Burp Suite / OWASP ZAP Scope Generator**: Exports target URLs, wildcards, and discovered sub-paths as an enterprise proxy scope file.

### ⚪ White Hat (Defensive / Engineering)
- **Zero-Trust Strict CSP Synthesizer**: Automatically analyzes all legitimate scripts, stylesheets, and CDN domains currently running on the page, then outputs a strict `default-src 'self'` policy with nonces and SHA hashes.
- **Compliance Crosswalk**: Real-time compliance breakdown for **NIST CSF 2.0**, **PCI-DSS v4.0**, and **ISO 27001**.
- **AI Remediation Prompts**: Pre-engineered prompt templates for Claude, ChatGPT, and GitHub Copilot to automatically refactor vulnerable code.

---

## 🛠️ Remediation & Hardening Suite

The built-in **Fix Center** writes production-ready configuration code for your exact tech stack:

<details>
<summary><strong>Click to view supported server and framework targets</strong></summary>

1. **Nginx** (`/etc/nginx/conf.d/security.conf`) — Hardened headers, SSL ciphers, and rate-limiting.
2. **Apache HTTP Server** (`.htaccess` / `httpd.conf`) — `mod_headers` and security directives.
3. **Caddy Server** (`Caddyfile`) — Modern automatic HTTPS and security header blocks.
4. **Cloudflare Transform Rules** — Edge-level response header injection rules.
5. **AWS WAF & CloudFront** — Response headers policy config and CloudFront functions.
6. **Next.js** (`next.config.js`) — `async headers()` configuration for SSR & Static sites.
7. **Node.js / Express** (`helmet` & custom middleware) — Zero-dependency security middleware.
8. **Docker Containerfile** — Unprivileged user execution, read-only root filesystems, and minimal attack surface.
9. **GitHub Actions CI/CD** — Automated DevSecOps quality gate workflow to block PRs with critical findings.

</details>

---

## 📊 Enterprise Reporting & Exports

Export high-fidelity security deliverables with a single click:

```
├── 📑 Executive Summary Report (HTML)
│   ├── Overall Health Index & Score Grade
│   ├── Risk Radar & Severity Distribution Charts
│   ├── Compliance Posture Overview (OWASP / NIST / PCI-DSS)
│   └── Top Remediation Priorities for Leadership
│
├── 🔬 Technical Pen-Test Audit (HTML)
│   ├── Detailed Finding Catalog with Status & Confidence
│   ├── CWE Identification & Exploitability Analysis
│   ├── MITRE ATT&CK Mapping & Threat Intelligence
│   └── Ready-to-Run Verification Payloads & cURL Snippets
│
├── 🎯 Burp Suite & OWASP ZAP Target Scope (JSON)
│   └── Importable scope definitions configured for active proxy testing
│
└── 📋 Raw Telemetry JSON Log
    └── Complete machine-readable audit payload for SIEM & automated pipelines
```

---

## 🔒 Commercial Code Armor & Intellectual Property Protection

The production release is safeguarded by an enterprise-grade compilation and obfuscation pipeline:

- **🔐 Base64 Dynamic String Encryption**: String literals, regex signatures, and rule tables are encrypted in runtime lookup ciphers.
- **🌀 Control-Flow Flattening**: Execution structures are flattened into randomized state-machine switch dispatchers.
- **⚙️ Hexadecimal Identifier Scrambling**: Variables and function names are scrambled into non-reversible hex symbols.
- **🛡️ Dead Code Injection**: Injects deceptive decoy execution paths that neutralize disassemblers.
- **🚫 Zero Source Leakage**: Production bundles are completely stripped of developer comments, notes, and formatting.

---

## 💻 Tech Stack & Architecture

- **Platform**: Google Chrome Extensions (Manifest V3)
- **Background Worker**: Service Worker with Event-driven Lifecycle
- **Security Audit Core**: Pure Native Vanilla JavaScript (ES2022)
- **Styling Architecture**: Custom Dark Glassmorphism CSS Design System
- **Dependencies**: **0 External Runtime Dependencies** (100% self-contained)
- **Performance**: Sub-100ms full audit execution time

---

## 📦 Installation & Usage

### Method 1: Load Pre-Built Production Package (Recommended)

1. Download or clone this repository:
   ```bash
   git clone https://github.com/Muhammad9985/AegisShield-Pro.git
   ```
2. Open Google Chrome and navigate to:
   ```
   chrome://extensions/
   ```
3. Enable **Developer mode** using the toggle switch in the top right.
4. Click **Load unpacked** in the top left corner.
5. Select the **`dist/`** folder from the project directory (or extract `AegisShield-Pro-Production.zip` and select the unzipped folder).
6. Pin **AegisShield Pro** to your Chrome toolbar and navigate to any website to start auditing!

### Method 2: Building from Development Source

If you wish to modify the source code and rebuild the production distribution:

```bash
# Clone the repository
git clone https://github.com/Muhammad9985/AegisShield-Pro.git
cd AegisShield-Pro

# Install build-time dev dependencies
npm install

# Run automated test suite
npm test

# Build obfuscated, production-ready distribution package
npm run build:dist
```

The compiled, encrypted distribution bundle will be generated in `dist/` alongside the ready-to-share `AegisShield-Pro-Production.zip`.

---

## 📜 Regulatory & Compliance Alignment

AegisShield Pro aligns with premier cybersecurity and regulatory compliance standards:

- **OWASP Top 10 (2021)**: A01 Broken Access Control, A02 Cryptographic Failures, A03 Injection, A05 Security Misconfiguration, A07 Identification and Authentication Failures.
- **NIST Cybersecurity Framework 2.0**: Identify (ID.AM, ID.RA), Protect (PR.AC, PR.DS, PR.PT), Detect (DE.CM).
- **PCI-DSS v4.0**: Requirement 4 (Protect Cardholder Data in Transit), Requirement 6 (Develop and Maintain Secure Systems).
- **ISO/IEC 27001:2022**: Annex A.8 (Technological Controls), A.8.20 (Network Security), A.8.24 (Use of Cryptography).

---

## 👨‍💻 Author & Connect

**AegisShield Pro** was designed and engineered by **Muhammad Rafique** under **MR Software**.

<p align="left">
  <a href="https://mr-software.online/" target="_blank">
    <img src="https://img.shields.io/badge/Website-mr--software.online-00dfa2?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" />
  </a>
  &nbsp;
  <a href="https://github.com/Muhammad9985" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Muhammad9985-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/muhammad-rafique-944b05159/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Muhammad%20Rafique-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---

## ⚖️ License & Copyright

© 2026 **MR Software** • **Muhammad Rafique**. All Rights Reserved.  
This software is provided for authorized defensive cybersecurity analysis, penetration testing, and security auditing. Use only on systems you own or have explicit, documented authorization to test.

<p align="center">
  <sub>Built with 🛡️ for a safer web by <a href="https://mr-software.online/">MR Software</a></sub>
</p>
