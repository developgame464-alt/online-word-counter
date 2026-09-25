# Security Policy

## About This Project

The **Online Word Counter** is a client-side web tool published as part of **Finite SEO Tools**.

This repository contains the front-end source code for the tool. Security reports concerning the source code, dependencies, third-party integrations, or the live implementation are welcome.

## Supported Versions

This project is currently maintained as a single active version.

| Version | Supported |
|---|---|
| Current `main` branch | ✅ Yes |
| Older commits/releases | ❌ No formal support |

Because the project is actively developed, the `main` branch should be treated as the primary supported version.

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it privately rather than publicly posting the details in a GitHub issue.

### Security Contact

**Email:** help.finitestore@gmail.com

When reporting a vulnerability, please include as much of the following information as possible:

- A clear description of the vulnerability
- The affected file, feature, or component
- Steps required to reproduce the issue
- A proof of concept, if available
- The potential security impact
- Browser, device, or environment information when relevant
- Any suggested mitigation or fix, if you have one

Please do **not** include passwords, API keys, private credentials, personal information, or other sensitive data in a report.

## What Happens After a Report

We will review valid security reports and, when additional information is required, may contact the reporter for clarification.

Depending on the severity and reproducibility of the issue, we may:

1. Verify the reported vulnerability.
2. Determine which repository or live implementation is affected.
3. Develop and test a fix.
4. Publish an updated version or commit when appropriate.
5. Document the security improvement when appropriate.

Response and remediation times may vary depending on the complexity and severity of the issue.

## Responsible Disclosure

Please allow reasonable time for the issue to be investigated and addressed before publicly disclosing detailed vulnerability information.

We appreciate responsible disclosure and ask security researchers not to:

- Access or modify other users' data.
- Attempt to obtain credentials or authentication information.
- Perform destructive testing.
- Disrupt availability of the live website.
- Conduct denial-of-service testing.
- Exploit a vulnerability beyond what is reasonably necessary to demonstrate it.
- Publish sensitive vulnerability details before a fix or coordinated disclosure.

## Scope

Security reports may relate to:

- Cross-site scripting (XSS)
- Unsafe handling of user-controlled input
- Malicious JavaScript execution
- Dependency vulnerabilities
- Insecure external resources or integrations
- Accidental exposure of secrets or credentials
- Security weaknesses introduced by repository changes
- Other vulnerabilities that could affect users or the project's security

The repository is primarily a front-end project. Issues in third-party services or infrastructure that are not controlled by this project may need to be reported to the relevant service provider.

## Out of Scope

The following generally do not qualify as security vulnerabilities in this project unless they create a demonstrable security impact:

- General UI/UX bugs
- Cosmetic issues
- Typographical errors
- Feature requests
- Performance complaints without a security impact
- Browser-specific display issues
- Vulnerabilities in unrelated third-party services
- Social engineering attempts against people or services

## Secrets and Sensitive Information

Do not commit sensitive information to this public repository.

Examples include:

- API keys
- Access tokens
- Passwords
- Private certificates
- Authentication credentials
- Private configuration values

If a secret is accidentally committed, removing it from the latest commit alone may not be sufficient because Git history can retain previous versions. Rotate or revoke the exposed credential as appropriate and then remove the secret from the repository history.

## Third-Party Dependencies and Services

The project may be deployed alongside third-party services depending on the production implementation.

Security issues caused exclusively by an external provider should normally be reported to that provider. However, if the project's implementation exposes users to additional risk because of how that service is integrated, please report the issue to the project using the security contact above.

## Security Updates

Security-related fixes may be incorporated into the repository through normal Git commits or other project updates.

Users should use the latest supported version of the project when possible.

## Acknowledgements

We appreciate responsible security researchers and contributors who help improve the safety and reliability of this project.

If you report a valid vulnerability, you may be acknowledged for your contribution if you provide a preferred name or handle and explicitly indicate that you are comfortable being credited.

## Contact

For security-related concerns:

**Kartik Garg**  
**Project:** Online Word Counter / Finite SEO Tools  
**Email:** help.finitestore@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/kartik-garg-628a96437

---

*Last updated: September 2026*
