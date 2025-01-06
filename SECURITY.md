# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in the rclone project, please follow these steps:

1. **Do Not Publicly Disclose**: Do not raise an issue in the public issue tracker or disclose the vulnerability publicly until it has been resolved.
2. **Use GitHub's Reporting Interface**:
   - Navigate to the [GitHub Security Advisories](https://github.com/rclone/rclone/security/advisories) page for rclone.
   - Provide a detailed description of the issue, including steps to reproduce it if possible.

We will acknowledge receipt of your report within **48 hours** and provide updates as we investigate and address the issue.

## Supported Versions

The following versions of rclone are currently supported with security updates:

| Version         | Supported          |
|-----------------|--------------------|
| Latest release  | ✅ Yes             |
| Older releases  | ⚠️ Limited support |

Please note that versions beyond one year of their release may not receive security patches.

## Security Patch Process

1. **Investigation**: The security team investigates the report and assesses its impact.
2. **Fix Development**: A patch is developed in a private branch to resolve the issue.
3. **Testing**: The fix undergoes thorough testing to ensure it resolves the vulnerability without introducing regressions.
4. **Public Release**: The patch is merged, and a new release is published.
5. **Disclosure**: A public advisory is issued detailing the vulnerability and its resolution.

## Guidelines for Responsible Disclosure

To protect the users of rclone, we request that you adhere to the following responsible disclosure guidelines:

- Allow sufficient time for the issue to be addressed before discussing it publicly.
- Work with us to verify the fix and ensure the vulnerability is resolved.

Thank you for helping to keep rclone secure!
