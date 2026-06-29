# Laundry Landing Page & Product Catalog Website

A clean, modern, and fully responsive static website designed for a laundry service business. This project was built from scratch using vanilla HTML, CSS, and JavaScript to demonstrate semantic markup, responsive layout techniques, and framework-free DOM manipulation for a portfolio piece.

---

## Key Features

- **Fully Responsive Layout** — Tailored for mobile, tablet, and desktop viewports using CSS Grid and Flexbox.
- **Dynamic Service Filtering** — Filterable service cards (All / Clothing / Premium / Specialty) using vanilla JS.
- **Interactive UI Components** — Custom FAQ accordion and a mobile hamburger menu built without third-party libraries.
- **Scroll-Triggered Animations** — Smooth fade-up effects powered by the native `IntersectionObserver` API.
- **Call-to-Action Integration** — Direct WhatsApp ordering integration mapped to individual service items.

---

## Pages Included

| File | Description |
|------|-------------|
| `index.html` | Homepage featuring a hero section, features list, process workflow, and about section. |
| `produk.html` | Services & Pricing page with functional category filters, promo banner, and an FAQ accordion. |

---

## Tech Stack & Tools

- **HTML5** — Semantic and accessible markup.
- **CSS3** — Custom properties (CSS variables), Flexbox, and Grid (Built completely from scratch, no Bootstrap/Tailwind).
- **Vanilla JavaScript** — Handles UI interactions, filters, accordions, and scroll animations.
- **Typography** — Playfair Display (Serif) + Inter (Sans-serif) via Google Fonts.
- **Icons** — Font Awesome 6 via CDN.

---

## Design System & Tokens

The project utilizes a centralized color palette and typography system via CSS Custom Properties:

| Token | Value | Usage |
|-------|-------|-------|
| `--ink` | `#0F1923` | Primary text and dark UI elements |
| `--ink-soft` | `#5C7080` | Secondary text and captions |
| `--cream` | `#F8F7F4` | Global page background |
| `--sky` | `#C8E6F5` | Accent fills and subtle background container shapes |
| `--mint` | `#2DD4BF` | Interactive highlights and primary CTA buttons |
| `--white` | `#ffffff` | Cards, structural containers, and footer background |

---

## Project Structure
liana-laundry/
├── index.html       # Homepage
├── produk.html      # Services & Pricing page
├── style.css        # Shared CSS tokens & reset
└── README.md

---

## Getting Started

Since this is a fully static project, there are no build tools, dependencies, or installation steps required. You can run it directly in any browser.

```bash
# Clone the repository
git clone [https://github.com/mabertha/liana-laundry-website.git]

# Navigate into the project directory
cd liana-laundry-website

# Open index.html directly in your default browser
# (Or right-click index.html and select "Open with Browser")
