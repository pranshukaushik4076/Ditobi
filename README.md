# Ditobi Filipino Restaurant — Website

A warm, minimalist, mobile-first website for **Ditobi**, a family-owned Filipino restaurant at 279 Grote Street, Adelaide. Built as a single, self-contained HTML file with embedded styles, scripts and images — no build step, no dependencies.

🔗 Repository: https://github.com/pranshukaushik4076/Ditobi

## Overview

Ditobi brings home-style Filipino cooking from Pampanga to the Adelaide CBD. The site is designed to feel authentic, welcoming and premium — encouraging visitors to browse the menu, find the restaurant and become regulars.

The entire site is one file, `index.html`. Just open it in a browser or drop it onto any static host.

## Features

- **Single-file build** — HTML5, CSS3 and vanilla JavaScript in one `index.html`. No frameworks, no bundler.
- **Sections** — Home (hero, welcome, featured dishes, opening announcement), Our Story, full Menu, Gallery, Visit Us and Contact.
- **Real photography** — Ditobi's own dishes and storefront, optimised and embedded as data URIs so nothing depends on external/expiring links.
- **Full menu** — Mains, Starters & Silogs, Sides & Extras, Desserts and Drinks, organised into tabbed categories with descriptions and prices.
- **Responsive & mobile-first** — fluid layout from phone to desktop, with a collapsible navigation menu.
- **Sticky navigation & smooth scrolling** between sections.
- **Google Maps** embed for the Grote Street location.
- **Contact form & newsletter signup** — front-end ready, validate and confirm on screen (need connecting to an email service to deliver).
- **Soft hover animations** and tasteful, subtle Filipino cultural cues (sun motif, warm palette).

## Design

- **Palette:** deep forest green, warm gold, cream, charcoal and natural wood tones — drawn from Ditobi's own branding.
- **Typography:** Fraunces (display serif) and Inter (body), via Google Fonts.
- **Principles:** generous white space, clean layout, fast loading, accessible.

## SEO & Accessibility

- Meta title, description and keywords targeting local Filipino-food searches.
- Open Graph / Twitter card tags for social sharing.
- **Schema.org `Restaurant`** structured data (address, geo, opening hours, cuisine, price range).
- Descriptive `alt` text on every image; semantic HTML, skip link, visible focus styles and a `prefers-reduced-motion` fallback (WCAG-minded).
- Lazy-loaded images for performance.

## Getting started

```bash
# Clone
git clone https://github.com/pranshukaushik4076/Ditobi.git
cd Ditobi

# Open locally — no build needed
open index.html        # macOS
```

### Deploy

Because it's a single static file, you can host it anywhere:

- **GitHub Pages** — Settings → Pages → deploy from the `main` branch.
- **Netlify / Vercel / Cloudflare Pages** — drag-and-drop `index.html`, or connect this repo.

## Restaurant details

- **Address:** 279 Grote Street, Adelaide SA 5000, Australia
- **Hours:** Wed–Sat 11am–9pm · Sun 12pm–9pm · Mon–Tue closed
- **Cuisine:** Filipino
- **Socials:** [Facebook](https://www.facebook.com/people/Ditobi-Filipino-Restaurant/61587026103978/) · [Instagram @ditobi_adl](https://www.instagram.com/ditobi_adl) · [TikTok @ditobi_adl](https://www.tiktok.com/@ditobi_adl)

## To do / customise

- Add a **phone number** and an **online ordering / booking** link.
- Connect the **contact form** and **newsletter signup** to an email service (e.g. Formspree or Netlify Forms).
- Swap in any additional photography as it becomes available.

## Project structure

```
.
├── index.html      # the entire website (markup, styles, scripts, images)
├── README.md
└── .gitignore
```

---

Made with care for Ditobi Filipino Restaurant. Mabuhay! 🇵🇭
