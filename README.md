# ☕ Lovora Coffee

> **Little moments. Lovely sips.**

Lovora is a multi-page, front-end website for a coffee shop based in F-7 Markaz, Islamabad. It showcases the brand story, a flavor showcase, a full drink menu with a working shopping cart, and a contact form that sends messages by email or WhatsApp.

Built with plain **HTML, CSS and vanilla JavaScript**. No frameworks, no build step, no backend.

---

## ✨ Features

- **Animated landing page** with a loading screen (shown once per session), a hero section, and a rotating drink showcase with Play / Pause / Next controls.
- **Flavors page** featuring signature drinks with tasting notes and an "Add to order" button.
- **Menu page** with:
  - 9 drinks with prices in Pakistani Rupees (Rs)
  - Category filters (All drinks, Coffee, Frappes, Refreshers) and search
  - Live cart with quantity controls and running total
  - Checkout summary
- **Our Story page** covering the brand philosophy and "Little Promise" values.
- **Contact page** with a form (name, phone, email, message) that sends via **Email** (`mailto:`) or **WhatsApp** (`wa.me`), plus opening hours and a Google Maps directions link.
- Fully static and easy to host anywhere.

---

## 📁 Project Structure

```
Lovora/
├── loader.html          # Home / landing page (entry point)
├── flavors.html         # Signature flavors
├── menu.html            # Full menu + cart + checkout
├── our-story.html       # Brand story
├── contact.html         # Contact form, hours, location
├── bean-left.png        # Decorative coffee bean
├── bean-right.png       # Decorative coffee bean
├── coffee-beans-bg.png  # Background texture
└── lovora-cups/         # Drink images
    ├── lovora-matcha.png
    ├── lovora-mint-mocha.png
    ├── lovora-caramel-cloud.png
    ├── lovora-cold-brew.png
    ├── vanilla-velvet-latte.webp
    ├── chocolate-hazelnut.webp
    ├── strawberry-breeze.webp
    ├── strawberry-matcha.webp
    └── citrus-mint-cooler.webp
```

---

## 🚀 Getting Started

No installation needed.

1. **Download or clone** the project.
2. Open **`loader.html`** in any modern browser.

Or serve it locally (recommended):

```bash
# Python
python -m http.server 8000

# or Node
npx serve .
```

Then visit `http://localhost:8000/loader.html`.

> **Note:** `loader.html` is the home page, and every other page links back to it. Rename it to `index.html` if you deploy to a host that expects that filename (and update the links accordingly).

---

## 🍹 Menu Highlights

| Drink | Price |
|---|---|
| Matcha Frappe | Rs 950 |
| Mint Mocha | Rs 900 |
| Caramel Cloud | Rs 950 |
| Cold Brew Cream | Rs 850 |
| Vanilla Velvet Latte | Rs 800 |
| Chocolate Hazelnut | Rs 950 |
| Strawberry Breeze | Rs 750 |
| Citrus Mint Cooler | Rs 700 |
| Strawberry Matcha | Rs 1,000 |

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3** (custom properties, responsive layout, animations)
- **Vanilla JavaScript** (cart logic, filtering, loader, slider, form handling)
- **Google Fonts**: Fraunces, DM Sans, Playfair Display, Anton
- **Font Awesome 6.5.2** (via CDN)

An internet connection is needed to load fonts and icons.

---

## ⚙️ Customization

| What to change | Where |
|---|---|
| Drink names, prices, descriptions | `menu.html` and `flavors.html` |
| Drink images | `lovora-cups/` |
| Business email & WhatsApp number | `contact.html` (`BUSINESS_EMAIL`, `WHATSAPP_NUMBER`) |
| Opening hours & address | `contact.html` |
| Social links (Instagram, Facebook) | `contact.html` footer / contact section |
| Fonts & colors | CSS `:root` variables / `<style>` block in each page |

---

## 📌 Notes & Known Limitations

- The cart and checkout are **front-end only**. Checkout currently shows an order summary alert; there is no payment or backend order processing.
- Cart data is held in memory and resets on page reload.
- Prices for some drinks (e.g. Matcha Frappe, Cold Brew Cream) differ between `flavors.html` and `menu.html`. Keep them in sync.
- Instagram and Facebook links currently point to the generic homepages. Replace them with Lovora's real profiles.

---

## 📞 Contact

- **Email:** hello@lovoracoffee.com
- **WhatsApp:** +92 318 9603070
- **Location:** F-7 Markaz, Islamabad, Pakistan
- **Hours:** Monday – Sunday, 10:00 AM – 11:00 PM

---

© 2026 Lovora Coffee. All rights reserved.
developer:Momina Farooq