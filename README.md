# IC Markets Landing Page

A single-page responsive landing page replica with a sticky header,
mobile hamburger menu, and CSS-built gold bars graphic.

## Structure
- `index.html` — all HTML, CSS, and JS in one file (no build step needed)

## Features
- Sticky header that stays pinned while scrolling
- Mobile hamburger menu (sticky dropdown attached below header)
- Responsive layout (desktop, tablet, mobile breakpoints at 980px / 768px / 480px)
- Sticky "Trading involves risk" disclaimer
- CTA buttons linked to:
  - Header "Open Account" → WhatsApp (wa.me link)
  - Hero "OPEN ACCOUNT NOW" → Gmail (mailto link)

## Setup
No build tools required. Just open `index.html` in a browser,
or deploy the file as-is to any static host (Netlify, GitHub Pages, Vercel, etc.)

## Customization notes
- Replace `15551234567` in the WhatsApp link with your real number
  (international format, no `+`, no spaces/dashes)
- Replace `youremail@gmail.com` in the mailto link with your real email
- Colors and fonts are defined as CSS variables at the top of the
  `<style>` block (`--bg-deep`, `--green`, `--gold-1`, etc.)

## Known limitations
- Gold bars graphic is built with CSS gradients (no external image dependency)