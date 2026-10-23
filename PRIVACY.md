# Privacy Policy: Tsundere Highlighter

Last updated: October 23, 2026

**The developer collects no data.** There are no servers, accounts, analytics, ads or tracking.

## What the extension does with data
- **Highlighted text:** read only when you click the 💢 button. With no AI provider configured, it never leaves your browser (replies are generated locally). If you configure an AI provider, the highlighted text (up to 2,000 characters) is sent directly from your browser to that provider (Anthropic, OpenAI, Google, OpenRouter, or the custom endpoint you entered) to generate a reply. That provider's privacy policy applies to it.
- **API key and settings:** stored only on your device in the browser's extension storage. The API key is encrypted at rest with AES-256-GCM, either with a random non-extractable key held in the extension's IndexedDB, or (if you set a passphrase) a key derived with PBKDF2-SHA256 (600,000 iterations). The passphrase is never stored. A passphrase-derived unlock key is kept in memory only and is cleared when the browser closes or you click "Lock now".
- **Network:** the extension contacts only the AI provider you select, and only when you click 💢.

## Your control
"Erase all data" in the popup deletes the saved key, settings and encryption key, and revokes the extension's site permissions. Uninstalling removes everything.

## Limits of the encryption
Encryption protects your key from being read out of your browser profile files. It cannot protect against malware running as you or someone using your unlocked browser in device mode. Use a passphrase for stronger protection, and use a key with a spending limit.

## Contact
dityaijay@gmail.com
