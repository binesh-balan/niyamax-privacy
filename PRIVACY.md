# NiyamaX Data Protection — Privacy Policy

**Effective date: 24 July 2026**

NiyamaX Data Protection is a browser extension deployed by organizations to
prevent accidental leakage of sensitive data into AI chat services. This policy
describes what the extension processes and what it does not.

## What the extension processes

- **Text entered on approved AI websites.** Text that you paste or type into
  the chat input on the AI services listed in the extension's permissions
  (chatgpt.com, chat.openai.com, claude.ai, gemini.google.com,
  copilot.microsoft.com) is sent to a security gateway **operated by your own
  organization** for a policy decision (allow, redact, warn, or block). The
  extension takes no action until a gateway URL is configured by you or your
  organization.
- **File names of attachments.** When you select or drop a file on those sites,
  the file's name, type, and size are checked. **File contents are never read.**
- **Authentication token.** If your organization enables sign-in, an access
  token is sent with each check so decisions are attributed to your account.
- **Extension health.** Every six hours the extension reports its version
  number and browser type to your organization's gateway.

## What the extension does NOT do

- No collection of browsing history — the extension runs **only** on the AI
  websites listed in its permissions and nowhere else.
- No keystroke logging — only the content of the chat input box on those sites
  is inspected.
- No reading of file contents.
- No storage of your text by the extension — content is checked and discarded.
- No advertising, analytics, tracking, or sale of data of any kind.
- No transmission of any data to the extension developer. All data goes only
  to the gateway your organization configures.

## Data retention and your organization

Policy decisions (category of detection, decision taken, timestamps — not the
underlying text, which is stored only as a cryptographic hash) are logged by
your organization's gateway for security auditing. Retention and access are
governed by your organization's policies; contact your IT or security team for
details.

## Local storage

The extension stores locally in your browser: your gateway settings, a signed
policy bundle used for offline enforcement, and (if sign-in is enabled)
authentication tokens. Removing the extension deletes this data.

## Changes and contact

Material changes to this policy will be reflected in the extension's store
listing. Questions: open an issue at
https://github.com/binesh-balan/Niyama-AI/issues
