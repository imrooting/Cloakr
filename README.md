# 🛡 Pentest Data Sanitizer

A single-file browser tool that redacts sensitive data from pentest output before you share it with AI tools or teammates.

**No install. No server. Just open the HTML file.**

---

## What it redacts

- IPv4 / IPv6 addresses
- Domains, FQDNs, pentest hostnames (`.htb`, `.lab`, etc.)
- MAC addresses
- Cookies & bearer tokens
- Anything else — just select text in the output to manually redact it

---

## How to use

1. Open `https://pages.github.com/imrooting/Cloakr/index.html` in any browser
2. Paste your pentest output (nmap, Burp, shell output, etc.) or upload a file
3. Click **Sanitize →**
4. Review the output — select any text to redact it, or click **✏ Edit** to edit directly
5. Copy / download the clean output, or click **🤖 Ask AI** to analyse it in-tool

---

## AI support

Works with Claude, ChatGPT, Gemini, and Grok. Enter your API key in the panel — it's stored in session memory only and gone when you close the tab. Claude users on claude.ai don't need a key at all.

---

## Security

Everything runs locally in your browser. Nothing is sent anywhere unless you use the AI panel. API keys are validated and never persisted to disk.

---

MIT License
