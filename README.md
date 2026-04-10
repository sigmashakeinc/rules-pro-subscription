# SigmaShake Pro Subscription Ruleset (Private)

This private, premium ruleset provides advanced developer security tailored for AI agents, including protection for Endpoint Detection and Response (EDR) solutions, credential safety, and data exfiltration prevention.

## Features
- **Protects Existing EDRs:** Prevents modification, stopping, or disabling of CrowdStrike Falcon and SentinelOne agents.
- **Prevents Data Exfiltration:** Blocks reverse shells, raw TCP/UDP socket connections, and potentially malicious payload downloads.
- **Credential Protection:** Prevents the AI agent from reading sensitive files like `.env`, AWS credentials, and SSH keys.

## Installation

```bash
ssg hub pull rules-pro-subscription
```
*(Requires a Pro subscription plan and authentication to access this private ruleset)*