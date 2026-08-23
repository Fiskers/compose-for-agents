# Security Policy

## Supported versions

Security fixes should target the latest version on the default branch.

## Reporting a vulnerability

Do not disclose suspected vulnerabilities in a public issue. Use GitHub's
**Security** tab and **Report a vulnerability** when private vulnerability
reporting is available, or contact the upstream Docker maintainers through a
verified private channel.

Include the affected demo, reproduction steps, impact, container configuration,
and a minimal proof of concept using disposable credentials and data.

Never include real MCP tokens, model-provider keys, Docker credentials,
personal data, or unredacted agent transcripts. Revoke exposed credentials.

## Safe use

These projects are development demonstrations, not production-hardened
deployments.

- Keep `.mcp.env` and secret files out of version control.
- Review MCP servers, tools, images, and model instructions before use.
- Treat retrieved content and model output as untrusted.
- Use least-privilege tokens and container permissions.
- Do not mount sensitive host directories or the Docker socket unless required.
- Bind services only to trusted interfaces.
- Pin and review third-party images before production use.
