# Nostra – Content Update Guide

Use this guide to replace placeholders with your actual content. All locations are listed with file paths and line references.

---

## 1. Canonical URLs & Domain

**Live URL (GitHub Pages):** `https://mohamed-asmaan.github.io/nostra/`

| File | Canonical / og:url |
|------|--------------------|
| `index.html` | `https://mohamed-asmaan.github.io/nostra/` |
| `collections.html` | `https://mohamed-asmaan.github.io/nostra/collections.html` |
| `contact.html` | `https://mohamed-asmaan.github.io/nostra/contact.html` |

---

## 2. Open Graph URLs (Social Sharing)

Same as above – update `og:url` in each page's `<head>` when you deploy.

---

## 3. Favicon

- **Current:** `assets/favicon.svg` – simple "N" on dark background
- **To customize:** Replace `assets/favicon.svg` with your own logo (SVG or add `favicon.ico` for older browsers)
- **Optional:** Add `apple-touch-icon.png` (180×180) for iOS home screen

---

## 4. Meta Description & Keywords

Update in each page's `<head>` if your brand or focus changes:

- **index.html** – Home page description
- **collections.html** – Collections page description  
- **contact.html** – Contact page description

---

## 5. Footer – Social Links

**File:** `index.html`, `collections.html`, `contact.html`

Replace `href="#"` with your real URLs:

```html
<a href="#" class="footer__social-link" aria-label="Instagram">
<a href="#" class="footer__social-link" aria-label="Twitter">
<a href="#" class="footer__social-link" aria-label="Facebook">
```

---

## 6. Footer – Brand Description

**File:** `index.html`, `collections.html`, `contact.html`

Current text: *"Nostra brings you curated fashion for every occasion – summer, beach, and party. Shop authentic styles with fast, free shipping."*

Replace with your actual brand tagline.

---

## 7. Hero Slider Images

**File:** `index.html`

Currently uses `./assets/slider-one.jpg` three times. Replace with your own hero images and update `alt` text to match each slide.

---

## 8. Product Images & Alt Text

**New Arrivals** (`index.html`):
- `na1.jpg` – Blue summer casual
- `na2.jpg` – Green beach style
- `na3.jpg` – Red party wear
- `na4.jpg` – White beach collection

**Most Wanted** (`index.html`):
- `mw-1.jpg` through `mw-8.jpg` – Update `alt` if product names change

**Collections** (`js/script.js`):
- Product data: `name`, `desc`, `price`, `src` – Edit the `products` array

---

## 9. Newsletter & Contact Forms

**Files:** All HTML pages with newsletter form; `contact.html` for contact form

- `action="#"` – Replace with your form handler URL (e.g. Formspree, Netlify Forms, or backend endpoint)
- `method="post"` – Keep as-is for most handlers

---

## 10. Copyright Year

**Files:** `index.html`, `collections.html`, `contact.html`

Current: `© 2025 Nostra. All rights reserved.`

Update the year when needed.

---

## Summary of Files to Edit for Your Content

| File | What to Update |
|------|----------------|
| `index.html` | Canonical, og:url, hero images, footer social links, footer description |
| `collections.html` | Canonical, og:url, footer social links, footer description |
| `contact.html` | Canonical, og:url, form action, footer social links, footer description |
| `js/script.js` | Product names, descriptions, prices, image paths (products array) |
| `assets/favicon.svg` | Replace with your logo |
