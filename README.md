# Golden Sands of Abu Abali — Company Website

A modern, responsive single-page website for **Golden Sands of Abu Abali**, a leading GRP (Glass Reinforced Plastic) and fiberglass manufacturer based in the Sultanate of Oman.

---

## 🌐 Live URL

[https://dyram.github.io/willy-golden-sands/](https://dyram.github.io/willy-golden-sands/)

---

## 📋 Project Overview

This is a static HTML/CSS/JS website with no build tools or dependencies required. It presents the company's products, services, vision, and contact information in a premium, dark-themed layout.

**Company:** Golden Sands of Abu Abali  
**Location:** Al Muladda, Al Musannah, Sultanate of Oman  
**Founded:** 2016 | Registered: 2018  
**C.R. No:** 120498

---

## ✨ Features

- **Fully static** — single `index.html` file, no framework or build step needed
- **Responsive design** — mobile, tablet, and desktop layouts
- **Smooth scroll reveal animations** — elements animate into view on scroll
- **Fixed navigation** — shrinks on scroll with active section highlighting
- **Mobile hamburger menu** — collapsible navigation for small screens
- **SEO optimised** — meta tags, Open Graph, Twitter Card, and JSON-LD structured data
- **Accessible** — semantic HTML, ARIA labels, and keyboard-friendly interactions
- **Contact form** — `mailto:` form pre-configured for the company email
- **Google Fonts** — Playfair Display, Barlow, and Barlow Condensed

---

## 🗂️ Project Structure

```
/
├── index.html              # Main (and only) HTML file
└── assets/
    └── imgs/
        ├── 1.jpeg          # About section — main facility image
        ├── 2.jpeg          # About section — accent image
        ├── 3.jpeg          # Vision section — image 1
        ├── 4.jpeg          # Vision section — image 2
        ├── 5.jpeg          # Gallery — Water Tanks
        ├── 6.jpeg          # Gallery — Bathroom Cabins
        ├── 7.jpeg          # Gallery — GRP Doors
        ├── 8.jpeg          # Gallery — Septic Tanks
        ├── 9.jpeg          # Gallery — Manholes & Covers
        ├── 10.jpeg         # Gallery — Cladding & Décor
        ├── 11.jpeg         # Why Choose Us — full-width image
        ├── 12.jpeg         # Why Choose Us — image 1
        └── 13.jpeg         # Why Choose Us — image 2
```

---

## 🚀 Getting Started

No installation or build process required.

1. **Clone or download** the repository
2. Place your product images in `assets/imgs/` (named `1.jpeg` through `13.jpeg`)
3. Open `index.html` in any modern browser

To serve locally with a simple HTTP server:

```bash
# Python 3
python -m http.server 8080

# Node.js (npx)
npx serve .
```

Then visit `http://localhost:8080`.

---

## 🛠️ Customisation

All styles are written in plain CSS using custom properties (variables) defined at the top of the `<style>` block. Key values to adjust:

| Variable       | Default   | Purpose                 |
| -------------- | --------- | ----------------------- |
| `--gold`       | `#d4a017` | Primary brand colour    |
| `--gold-light` | `#f0c842` | Hover / highlight shade |
| `--dark`       | `#111111` | Page background         |
| `--light`      | `#f8f5ef` | Primary text colour     |
| `--sand`       | `#f2e8d5` | Warm accent background  |

---

## 📦 Sections

| Section  | ID          | Description                           |
| -------- | ----------- | ------------------------------------- |
| Hero     | `#hero`     | Full-screen intro with stats and CTAs |
| About    | `#about`    | Company history, pillars, and imagery |
| Vision   | `#vision`   | Mission statement and goals           |
| Services | `#services` | 9-card grid of product categories     |
| Products | `#products` | Asymmetric photo gallery              |
| Why Us   | `#why`      | Key differentiators with imagery      |
| Welcome  | `#welcome`  | GM message / quote                    |
| Contact  | `#contact`  | Contact details and enquiry form      |

---

## 📇 Contact

|                      |                                                   |
| -------------------- | ------------------------------------------------- |
| **Phone / WhatsApp** | +968 96060358 · +968 79893268                     |
| **Email**            | Goldensandsmct2020@gmail.com                      |
| **Address**          | Al Muladda, Al Musannah, P.B. 320, P.C. 312, Oman |

---

## 📄 License

© 2026 Golden Sands of Abu Abali. All rights reserved.
