# Security baseline

- Never commit `.env`, private keys, tokens, passwords or recovery codes.
- Use environment variables and GitHub Actions secrets for deployment credentials.
- Give workflows minimum `permissions`.
- Pin third-party Actions to full commit SHAs for sensitive production workflows.
- Keep dependencies updated.
- Do not test college or third-party systems without explicit written authorisation.
- Report vulnerabilities privately.
- Remove access promptly when a contributor leaves.
