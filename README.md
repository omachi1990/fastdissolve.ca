# fastdissolve.ca

Official Canadian Corporate Dissolution Platform (`fastdissolve.ca`).

Close Canadian Corporations and Limited Partnerships (Federal CBCA & all 10 Provinces / 3 Territories) 100% online in 24 hours.

---

## 🚀 Features

- **Multi-View Single Page Application (SPA):**
  - **Homepage:** Hero section with inline 2-step dissolution lookup, trust signals, government-adjacent Canadian design.
  - **About Us:** Corporate background, mission, and Canadian registry compliance.
  - **Contact Us:** Interactive inquiry form with direct support email.
  - **Animated Review Sequence:** Real-time animated verification checklist before checkout.
  - **Checkout & Payment:** Dynamic fee calculation ($295 flat service fee + provincial registry filing fees) for Federal + all 13 provinces & territories, with mock Stripe/card validation.
  - **Get Started Modal:** 2-step quick questionnaire accessible from any page.
- **Brand Assets:**
  - Standardized SVG vectors in `assets/logos/` (Light, Dark, Transparent, Canadian Modernist).
  - High-resolution banners and posters in `assets/banners/fastdissolve/`.

---

## 📂 Project Structure

```
fastdissolve.ca/
├── index.html                   # Main Production Web Platform
├── assets/
│   ├── logos/                   # Official SVG Vector Logos
│   │   ├── logo-horizontal-light.svg
│   │   ├── logo-horizontal-dark.svg
│   │   ├── logo-mark-darkbg.svg
│   │   ├── logo-mark-transparent.svg
│   │   └── logo-maple-lockup.svg
│   └── banners/fastdissolve/    # Banners, posters & previews
│       ├── minimalist-swiss-1080x1080.png
│       ├── minimalist-dark-1080x1080.png
│       ├── minimalist-canadian-1080x1080.png
│       └── website-preview.png
└── docs/
    └── fastdissolve_canada_web_platform.html
```

---

## 💻 Quick Start & Preview

Open `index.html` directly in any modern browser, or run a local static server:

```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve .
```
