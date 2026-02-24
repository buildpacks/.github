# Security Policy

This security policy outlines procedures for reporting vulnerabilities, coordinating fixes, and disclosing security issues in Cloud Native Buildpacks projects.

## Reporting a Vulnerability

We strongly encourage people to report security vulnerabilities privately to our security team before disclosing them in a public forum.

There are two ways to report a vulnerability:

1. **GitHub Security Advisories**: Use the [Report a vulnerability](https://github.com/buildpacks/community/security/advisories/new) feature in the Security tab of the `buildpacks/community` repository.
2. **Email**: Send a report to [security@buildpacks.io](mailto:security@buildpacks.io).

The PGP fingerprint for the security email is: `7AA4 452E A0C3 56F8 894D C869 4E56 F857 5412 6F64`

It can be obtained from a public key server such as pgp.mit.edu.

Please note that these channels should only be used for reporting undisclosed security vulnerabilities in Cloud Native Buildpacks products. We cannot accept regular bug reports or other security-related queries through these channels.

### What to Include in a Report

To help us triage and respond quickly, please include as much of the following as possible:

- Affected software and versions
- Steps to reproduce the vulnerability
- Description of the impact or potential consequences
- Suggested severity (e.g., low, medium, high, critical)
- Any relevant logs, screenshots, or proof-of-concept code

## Response Process

1. **Acknowledgment**: The security team will acknowledge receipt of your report within 72 hours.
2. **Triage**: A maintainer will be assigned to investigate and validate the issue. If additional information is needed, they will reach out to the reporter directly.
3. **Advisory Draft**: Once confirmed, the maintainers will create a draft GitHub Security Advisory to coordinate discussion with the reporter and relevant maintainers.
4. **Fix Development**: A fix will be developed privately. A timeline for the patch and disclosure date will be agreed upon with the reporter.
5. **Disclosure**: Once the fix is released, the security advisory will be published and the vulnerability disclosed publicly through GitHub Security Advisories and project release notes.

We aim to resolve confirmed vulnerabilities promptly and will keep reporters informed throughout the process.

## Supported Versions

Security fixes are applied to the latest release of each Cloud Native Buildpacks project. Users are encouraged to stay on the most recent release to receive security updates.

## Public Disclosure

Resolved vulnerabilities are disclosed through:

- [GitHub Security Advisories](https://github.com/buildpacks/community/security/advisories)
- Release notes for the affected project

## Audits

* The Cloud Native Buildpacks project completed a third party security audit on 2024-07-17 funded by the CNCF. You can view the audit report on the [OSTIF blog](https://ostif.org/buildpacks-audit-complete/).
* As part of the incubation process, the Cloud Native Buildpacks project completed a self assessment on 2021-09-07. The self assessment can be found in the [`cncf/toc` repo](https://github.com/hone/toc/blob/master/projects/buildpacks/security-assessment/self-assessment.md).
