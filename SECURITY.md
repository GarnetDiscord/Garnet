# Garnet Security Policy

**Last updated: 4 October 2026**

The Garnet team takes the security of Garnet and the information it processes seriously.

If you discover a potential security vulnerability, please report it privately rather than publicly disclosing it before the issue can be investigated.

## 1. Reporting a Vulnerability

Please report security vulnerabilities through the [Garnet Discord Server](https://dsc.gg/garnetbot).

When reporting an issue, include as much of the following as you can safely provide:

- A clear description of the vulnerability
- The affected feature or component
- Steps to reproduce the issue
- The potential impact
- Relevant logs, screenshots, or proof-of-concept information

Do not include passwords, tokens, private user information, or other unnecessary sensitive data.

## 2. Responsible Disclosure

Please allow the Garnet team reasonable time to investigate and address a reported vulnerability before publicly disclosing technical details.

When testing, do not:

- Access data that does not belong to you
- Modify or delete other users' data
- Disrupt Garnet or Discord services
- Perform denial-of-service attacks
- Social-engineer users or staff
- Publish credentials, tokens, or private information

Only test systems and data that you are authorised to access.

## 3. Scope

This policy applies to Garnet services and components that are operated by the Garnet team and explicitly made available for testing.

The Garnet source code is currently maintained in a private repository.

Vulnerabilities that belong exclusively to Discord or another third-party service should be reported to the relevant provider.

## 4. Credential Security

Discord bot tokens, API credentials, database credentials, and other secrets must not be intentionally published in source code or public repositories.

If a credential is accidentally exposed, it should be considered compromised and revoked or rotated as soon as possible.

## 5. Security Practices

Depending on the component, Garnet may use measures such as:

- Least-privilege access controls
- Secure secret handling
- Database access controls
- Dependency updates
- Logging and monitoring where appropriate
- Private source-code repository access controls

Security practices may evolve as Garnet develops.

## 6. Security Updates

Security fixes may be released through normal Garnet updates.

The amount of technical detail disclosed publicly may depend on the severity and nature of the vulnerability.

## 7. Contact

Security reports can be submitted through the [Garnet Discord Server](https://dsc.gg/garnetbot).

For sensitive reports, avoid posting confidential details in a public channel and request a private reporting method.

---

© 2026 Garnet. All rights reserved.
