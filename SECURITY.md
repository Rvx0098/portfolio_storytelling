# Security Policy

## Supported Versions

This is a static portfolio site. Security updates are applied to the default branch.

| Version | Supported |
| --- | --- |
| Default branch | Yes |

## Reporting a Vulnerability

If you find a security issue, please avoid opening a public issue with exploit details. Contact the maintainer privately through the contact information listed on the portfolio or GitHub profile.

Please include:

- A clear description of the issue
- Steps to reproduce
- Potential impact
- Suggested fix, if known

## Security Notes

- No secrets or API keys are required by the current static site
- `.env` files are ignored by Git and should never contain committed credentials
- Third-party scripts should be reviewed before they are added
- Any future backend or contact form should validate input server-side
- Any future analytics or AI integration should use deploy-time environment variables, not hardcoded credentials
