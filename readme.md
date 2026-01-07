📘 SLATE Docs (Legacy)

A minimal, clean documentation website built with pure HTML & CSS — no JavaScript, no build tools.

This repository represents the legacy (v1) documentation, kept live for backward compatibility, while a newer enhanced version (v2) is available separately.

🚨 Legacy Notice

This is the legacy version of SLATE Docs.

👉 New Documentation (v2):
https://docs.yoursite.com/v2

The legacy site includes a sticky, dismissible upgrade banner that guides users to the latest version without forcing redirects.

✨ Features

📄 Pure HTML & CSS only

🧭 Clean documentation layout (Header · Sidebar · Content)

📱 Fully responsive

🧩 Modular CSS architecture

⚠️ Sticky legacy warning banner

❌ Manually closeable banner (pure CSS checkbox hack)

🔗 Clear navigation to new documentation (v2)

🚫 No JavaScript

🚫 No dependencies

🚫 No build step

🖼️ Layout Overview
┌─────────────────────────────┐
│ Sticky Legacy Warning Bar   │
├─────────────────────────────┤
│ Header (Logo + Nav)         │
├──────────────┬──────────────┤
│ Sidebar Nav  │ Main Content │
│              │              │
├──────────────┴──────────────┤
│ Footer                      │
└─────────────────────────────┘

📁 Project Structure
slate-docs/
│
├── index.html
├── styles/
│   ├── base.css        # Reset & base styles
│   ├── layout.css     # Page layout (header, sidebar, content)
│   └── components.css # Callouts, buttons, utilities
│
└── README.md

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/your-username/slate-docs.git

2️⃣ Open locally

Simply open index.html in your browser.

That’s it.
No install. No build. No tooling.

⚠️ Legacy Upgrade Banner (How It Works)

The banner is sticky at the top

Uses CSS Grid for perfect centering

Uses a hidden checkbox to allow manual close

No JavaScript

Reappears on page refresh (intentional)

This follows industry-standard docs UX used by Stripe, GitHub, AWS, and Vercel.

🔄 Versioning Strategy
Version	Status	URL
v1	Legacy	/v1 or current site
v2	Active	/v2

Why keep v1 live?

Existing users rely on it

Prevents breaking bookmarks

Allows gradual migration

Professional documentation practice

🛠️ Customization

You can easily:

Update the new docs URL

Change banner colors

Make banner persistent (with JS + localStorage)

Add a version switcher

Add SEO noindex for legacy

📌 Recommended Enhancements (Optional)

Version badge (v1 · Legacy)

Dismiss animation

Persistent banner close

Dark/light theme sync

Reverse link from v2 → v1

Changelog page

📜 License

This project is open-source and free to use.
Choose a license that fits your needs (MIT recommended).

🙌 Credits

Built with ❤️ using HTML & CSS only
Inspired by modern documentation systems.

