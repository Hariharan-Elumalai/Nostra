# Nostra – E-commerce Website

A responsive e-commerce website built with HTML, CSS, and JavaScript. Features a fashion-focused design with summer collections, product filtering, and search functionality.

**Live Demo:** [https://mohamed-asmaan.github.io/nostra/](https://mohamed-asmaan.github.io/nostra/)

**Reference:** [Nostra E-commerce (Error Makes Clever)](https://errormakesclever.github.io/Nostra-Ecommerce-Js/index.html)

---

## Assignment Requirements

### Pages to Include

| Page | File | Status |
|------|------|--------|
| Home Page | `index.html` | ✅ |
| Collections Page | `collections.html` | ✅ |
| Contact Us Page | `contact.html` | ✅ |

### Functionality

| Feature | Location | Status |
|---------|----------|--------|
| Search functionality | Collections page – search by product name | ✅ |
| Filter functionality | Collections page – Occasion, Colors, Arrivals | ✅ |

### Files Created

| File | Purpose |
|------|---------|
| `index.html` | Home Page |
| `collections.html` | Collections Page |
| `contact.html` | Contact Us Page |
| `css/style.css` | Styling for all pages |
| `js/script.js` | JavaScript – search, filter, offer bar, drawer, slider, wishlist |

### Final Output

- ✅ Fully responsive e-commerce website
- ✅ Search and filter features working smoothly using JavaScript

---

## Project Structure

```
Nostra/
├── index.html          # Home page
├── collections.html    # Collections page (search & filter)
├── contact.html        # Contact Us page
├── css/
│   └── style.css       # Shared styles
├── js/
│   ├── script.js       # Shared logic + search & filter
│   └── contact.js      # Contact form handling
├── assets/
│   ├── favicon.svg
│   ├── brands/         # Brand logos
│   ├── products/       # Product images
│   └── ...
├── CONTENT_GUIDE.md
└── README.md
```

---

## Features

- **Home Page:** Hero slider, brands, services, new arrivals, most wanted, promo, newsletter
- **Collections Page:** Search by product name, filter by occasion (Summer/Party/Beach), color (Red/Blue/White/Green), and arrival (New/Old)
- **Contact Page:** Contact form and newsletter signup
- **Responsive:** Mobile-friendly with hamburger menu drawer
- **Accessibility:** Skip link, ARIA labels, semantic HTML

---

## How to Run

**Local:**
1. Clone or download the project
2. Open `index.html` in a browser, or
3. Use a local server (e.g. Live Server, `npx serve`, or `python -m http.server`)

**GitHub Pages:** Enable in repo Settings → Pages → Source: Deploy from branch → Branch: `main` → Save. Site will be live at [https://mohamed-asmaan.github.io/nostra/](https://mohamed-asmaan.github.io/nostra/)

---

## Technologies

- HTML5
- CSS3 (Flexbox, Media Queries)
- JavaScript (traditional, no frameworks)
