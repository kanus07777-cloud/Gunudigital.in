# Gunu Digital Security Setup

This is a static website, so it has a relatively small attack surface. No website can honestly be guaranteed impossible to hack.

## Included
- `.htaccess` security headers
- Directory listing disabled
- Clickjacking protection
- MIME sniffing protection
- Referrer policy
- Permissions policy
- Content Security Policy
- HTTPS/HSTS header
- Blocking of common sensitive files

## Hostinger / Cloudflare checklist
1. Enable SSL/HTTPS and force HTTPS.
2. Enable 2FA on Hostinger and domain account.
3. Use a unique strong password; never share it.
4. Keep the website static unless a backend is necessary.
5. Do not put passwords, API keys, database credentials, or payment secrets in HTML/JS.
6. Keep regular backups.
7. If Cloudflare is used, enable its security/WAF protections.
8. If you later add login, payments, admin panel, or a database, secure the backend separately; these HTML headers alone are not sufficient.
