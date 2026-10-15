# PDF Tools by Novatix

**8 free PDF tools. No uploads. No signup.**

🔗 **Live:** https://pdf.novatix.agency

A complete PDF toolkit that runs 100% in your browser — your files never leave your device. Merge, split, compress, convert, rotate, watermark, and more.

## 🛠️ The 8 Tools

| Tool | What it does |
|------|--------------|
| **Merge PDF** | Combine multiple PDFs into one |
| **Split PDF** | Extract pages or split into separate files |
| **Compress PDF** | Reduce file size without visible quality loss |
| **PDF → Images** | Convert PDF pages to PNG/JPG |
| **Images → PDF** | Turn images into a PDF document |
| **Rotate PDF** | Rotate pages 90°/180°/270° |
| **Watermark** | Add text watermarks to pages |
| **Page Numbers** | Add page numbers anywhere on the page |

## ✨ Features

- **🔒 100% client-side** — powered by `pdf-lib`; files are processed locally, never uploaded to any server
- **👤 Accounts (optional)** — login with Novatix SSO for a personal dashboard (`app.html`) with onboarding, file history, and AI tool suggestions
- **📊 Usage limits** — 5 files/day anonymous, 50/day logged in (generous free tier)
- **🛡️ CAPTCHA + brute-force protection** — canvas CAPTCHA on login, 5-fail/5-min lockout
- **🔗 Deep links** — every tool opens directly via `?tool=<id>`
- **🌙 Dark Obsidian theme** — consistent Novatix branding, SEO + JSON-LD on every page

## 🛠️ Tech

- Static frontend (`index.html`, `app.html`, `login.html`) — no build step
- PDF processing via `pdf-lib` (client-side)
- Auth via Novatix SSO shared cookies (`Domain=.novatix.agency`); backend API at `https://novatix.agency/api/v1/auth.php`
- OAuth: dedicated Google + GitHub apps for the `pdf.novatix.agency` subdomain

## 🚀 Deploy

```bash
# Static files — copy to web root
cp index.html app.html login.html favicon.* logo.png /var/www/html/
```

## 📄 License

© 2026 Novatix Agency. All rights reserved.
