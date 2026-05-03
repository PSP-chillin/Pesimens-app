# Security

This repository is intentionally limited to public-facing documentation and example configuration.

## Data handling

- No plaintext passwords are stored in the repository.
- No production secrets are checked in.
- API keys, service-role keys, JWT secrets, sync secrets, and payment secrets must come from environment variables or a secret manager.
- Example env files contain placeholders only.

## Operational controls

- Sensitive files such as `.env`, `.env.local`, uploads, logs, and build outputs should remain untracked.
- Production access should use least-privilege credentials.
- Authentication, payment, and sync integrations should be configured outside the public repo.

## Transparency notes

If you publish this repo publicly, keep the source code private and use this repository only to describe:

- product overview
- security posture
- privacy and data-handling principles
- deployment model
- contact path for security issues

## Recommended public disclosures

- what user data is collected
- where data is stored
- how secrets are managed
- whether credentials are encrypted
- how to report a vulnerability
