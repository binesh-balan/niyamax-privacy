# NiyamaX Data Protection

NiyamaX Data Protection is an enterprise browser extension that prevents
accidental leakage of sensitive company data into AI chat services
(ChatGPT, Claude, Gemini, Copilot).

## What it does

- **Blocks credentials** — API keys, private keys, passwords and connection
  strings are stopped before they reach an AI service
- **Redacts personal data** — emails, phone numbers, names, national IDs and
  salary figures are replaced with placeholders automatically
- **Screens file uploads** — risky file names (.env, .pem, id_rsa, ...) are
  blocked; file contents are never read
- **Coaches users** — clear explanations and a business-justification workflow
  instead of silent blocking
- **Works offline** — a cryptographically signed policy cache keeps blocking
  credentials even when the security gateway is unreachable

The extension requires a NiyamaX security gateway operated by your
organization. Without a configured gateway it takes no action. It collects no
browsing history, does not log keystrokes, and never stores your content —
see the [Privacy Policy](PRIVACY.md).

## Support

Questions, bug reports or false-positive reports: please
[open an issue](https://github.com/binesh-balan/niyamax-privacy/issues)
or contact your organization's IT security team.
