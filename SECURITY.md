# Security policy

Thank you for helping keep Novantra and our users safe. This document explains how to report a security vulnerability and what to expect from us in return.

## Please do not file a public Issue

Do **not** file a security vulnerability as a public GitHub Issue or post it in Discussions. Public disclosure before a fix is in place puts users at risk.

## How to report

Pick one of these channels, in order of preference:

1. **GitHub Private Vulnerability Reporting** (preferred). Use the **Report a vulnerability** button on this repository's [Security tab](https://github.com/novantra/community/security). This opens a private advisory visible only to you and Novantra maintainers.
2. **Email** `security@novantra.io`. Use plain text or, if you prefer, PGP (contact us first for our key).

If you do not receive an acknowledgement within five business days, please follow up by email.

## What to include in your report

The more of this we have, the faster we can act:

- A clear description of the issue and its potential impact.
- The exact version, build, or deployment where you observed it (Novantra Cloud, on-premise install version, or commit reference if you have one).
- Reproduction steps, with sample requests or screenshots if relevant.
- Any proof-of-concept code, redacted of real customer data.
- Your name and contact information so we can follow up; tell us whether you want to be publicly credited.

## What to expect from us

- **Acknowledgement** of receipt within five business days.
- **Initial assessment** of severity and reproducibility within ten business days.
- **Ongoing updates** at least every two weeks while the issue is being investigated and remediated.
- **Credit** in the eventual public advisory if you would like it, after the fix is released.

## Scope

In scope:

- The Novantra Cloud service.
- Novantra on-premise builds we publish.
- The `/api/v1/...` public API surface.
- The Novantra documentation site at `docs.novantra.io` (security-relevant issues only; for content feedback, use a public Issue).
- The Novantra marketing site at `novantra.io`.

Out of scope:

- Findings that require physical access to a user's device or account.
- Social engineering of Novantra staff, customers, or contractors.
- Denial-of-service via volumetric attacks.
- Third-party services we depend on (please report to the service in question).
- Issues in customer-deployed on-premise installs that result from local misconfiguration (please contact your account team).
- Reports based solely on automated scanner output without demonstrated impact.

## Coordinated disclosure

We follow a coordinated-disclosure model with a target timeline of 90 days from confirmed receipt to public advisory. We can extend or compress the window in agreement with the reporter when complexity or active exploitation warrant it.

We will publish a security advisory and (where applicable) a CVE once a fix is generally available.

## Safe harbor

If you make a good-faith effort to comply with this policy during your research, we will not pursue legal action against you and will work with you on coordinated disclosure. Please:

- Avoid privacy violations, destruction of data, and interruption or degradation of service.
- Only interact with accounts you own or for which you have explicit permission from the account holder.
- Do not exfiltrate any data; use the minimum needed to demonstrate the issue.

Thank you.
