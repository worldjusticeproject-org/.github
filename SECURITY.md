# Security Policy

The World Justice Project (WJP) takes the security of our software, data, and the communities we serve seriously. We appreciate the work of security researchers and the open-source community in helping us identify and address vulnerabilities responsibly.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

Instead, please report them through one of the following private channels:

### Preferred: GitHub Private Vulnerability Reporting

If the affected project has [Private Vulnerability Reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) enabled, open a report from the repository's **Security** tab → **Report a vulnerability**. This is the fastest way to reach the right maintainers.

### Email

If private reporting is not available, email us at:

📧 **security@worldjusticeproject.org** *(replace with the actual security contact)*

If you would like to encrypt your report, please request our PGP key in your initial (unencrypted) message.

### What to Include

To help us triage quickly, please include as much of the following as you can:

- The repository, branch, or release affected.
- The type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, exposed credentials, data leak, supply-chain risk).
- The location of the affected source code (file path, line number, commit SHA, or URL).
- Step-by-step instructions to reproduce the issue.
- Proof-of-concept or exploit code, if available.
- The impact of the issue, including how an attacker might exploit it.
- Any suggested mitigation or fix, if you have one in mind.

## Our Commitment

When you report a vulnerability to us, we will:

1. **Acknowledge** receipt of your report within **3 business days**.
2. **Triage** the report and provide an initial assessment within **10 business days**.
3. Keep you **informed** of progress toward a fix and disclosure.
4. **Credit** you in the security advisory and release notes (unless you prefer to remain anonymous).
5. **Coordinate** public disclosure with you once a fix is available, typically within 90 days of the initial report.

We follow a coordinated disclosure model and ask that you give us a reasonable amount of time to investigate and remediate before any public disclosure.

## Scope

This policy applies to all repositories owned by the **WorldJusticeProject** GitHub organization unless a specific repository defines its own `SECURITY.md`, in which case the repository-specific policy takes precedence.

### In Scope

- Source code and packaged releases hosted in this organization.
- Datasets and data pipelines published by WJP, where a vulnerability could lead to data integrity issues, unintended disclosure, or misrepresentation of findings.
- Public-facing tools, APIs, or services maintained from these repositories.

### Out of Scope

- Vulnerabilities in third-party dependencies — please report those upstream first; we will track and update as fixes become available.
- Issues on the main `worldjusticeproject.org` website or other WJP-operated web properties not hosted in this GitHub organization — please contact [info@worldjusticeproject.org](mailto:info@worldjusticeproject.org).
- Social-engineering, physical-security, or denial-of-service findings.

## Supported Versions

Unless a repository specifies otherwise, security fixes are provided for:

- The **latest released version** of each project.
- Datasets and indices for the **most recent edition** (e.g., the current year of the WJP Rule of Law Index®).

Older releases and prior editions of WJP datasets are archived and generally not patched, but we will note known issues in the relevant release notes or `README`.

## Safe Harbor

We will not pursue legal action against researchers who:

- Make a good-faith effort to comply with this policy.
- Avoid privacy violations, destruction of data, and disruption of services.
- Only interact with accounts they own or have explicit permission to access.
- Give us reasonable time to investigate and remediate before any public disclosure.

Thank you for helping keep WJP and our community safe.
