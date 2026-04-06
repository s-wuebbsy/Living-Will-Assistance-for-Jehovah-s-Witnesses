# Security Policy

## Architecture

This tool is a **single HTML file** that runs entirely in the browser. There is:

- No server or backend
- No external API calls
- No analytics or tracking
- No user accounts or authentication
- No data transmission of any kind

Decisions are stored in the browser's `localStorage` and never leave the device.

## Reporting a Vulnerability

If you discover a security issue (e.g. an XSS vector, a way to exfiltrate localStorage data, or a problem with the generated text), please open an issue describing the concern.

Given the fully client-side nature of this tool, the attack surface is minimal. However, we take any report seriously — especially since the tool handles sensitive personal medical decisions.

## Supported Versions

Only the latest release is supported. Please make sure you are using the most recent version before reporting an issue.
