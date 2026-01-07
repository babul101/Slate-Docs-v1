# 📘 SLATE Docs — Legacy Version (v1)

A clean, minimal documentation website built using only **HTML and CSS**.  
No JavaScript. No frameworks. No build tools.

> This repository contains the **legacy (v1)** documentation, which is intentionally kept live while a newer, enhanced version (**v2**) exists.

---

## 🚨 Legacy Documentation Notice

This is the **legacy version (v1)** of SLATE Docs.

👉 **New & Enhanced Docs (v2):**  
[https://docs.yoursite.com/v2](https://docs.yoursite.com/v2)

> To guide users safely, the site includes a **sticky, manually closeable warning banner** that links to the new documentation — without forcing redirects.  
This follows the same pattern used by **Stripe**, **GitHub**, **AWS**, and **Vercel**.

---

## ✨ Features

- ✅ Pure HTML & CSS only  
- ✅ No JavaScript  
- ✅ No dependencies  
- ✅ No build step  
- ✅ Fully responsive layout  
- ✅ Clean documentation structure (**Header · Sidebar · Content**)  
- ✅ Modular CSS architecture  
- ✅ Sticky legacy warning banner  
- ✅ Manually dismissible banner (CSS-only checkbox hack)  
- ✅ Clear navigation to new docs (v2)

---

## 🧱 Layout Overview

```text
┌─────────────────────────────────┐
│ Sticky Legacy Warning Banner    │
├─────────────────────────────────┤
│ Header (Logo + Navigation)      │
├───────────────┬─────────────────┤
│ Sidebar Nav   │ Main Content    │
│               │ Documentation   │
├───────────────┴─────────────────┤
│ Footer                          │
└─────────────────────────────────┘
```
## 📁 Project Structure

slate-docs/
│
├── index.html
├── styles/
│   ├── base.css         # Reset & base styles
│   ├── layout.css       # Page layout (header, sidebar, content)
│   └── components.css   # Callouts, utilities, components
│
└── README.md
---
## 🚀 Getting Started
1. Clone the repository
git clone https://github.com/babul101/slate-docs.git

2. Open locally
   Open index.html directly in your browser.
   That’s it — no installation, no tooling, no configuration.

⚠️ Legacy Warning Banner (Technical Details)
The legacy banner is:

Sticky using position: sticky

Perfectly centered with CSS Grid

Manually closeable using a hidden checkbox

JavaScript-free

Reappears on refresh (intentional for legacy notices)

Why no JavaScript?
Keeps the project minimal

Avoids runtime dependencies

Aligns with the static-docs philosophy

🔄 Documentation Versioning Strategy
Version	Status	Purpose
v1	Legacy	Backward compatibility
v2	Active	New features & enhancements
Why keep v1 live?
Existing users still depend on it

Prevents broken bookmarks

Enables gradual migration

Follows professional documentation practices

🛠️ Customization Guide
You can easily:

Change the new docs URL

Adjust banner colors

Move banner CSS into a stylesheet

Add a version badge (e.g. v1 · Legacy)

Add a noindex meta tag for SEO on legacy pages

Introduce persistent dismissal (optional, with JS)

🔮 Recommended Next Enhancements
Version switcher dropdown

Migration guide (v1 → v2)

Changelog page

Reverse link from v2 → v1

Dark/light theme support

Documentation deprecation timeline

📜 License
This project is open source.
MIT License is recommended for maximum flexibility, but you may choose any license that fits your needs.

🙌 Credits
Built with ❤️ using HTML & CSS only.
Inspired by modern documentation systems.   
