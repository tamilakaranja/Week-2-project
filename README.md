# COUTURE ~ Modern Fashion

A responsive fashion product showcase website built with HTML and CSS. COUTURE is a streetwear and fashion brand, and the site shows off a product grid, product detail modals, a cart section and a dark mode, all powered by CSS alone.

**Live demo:** https://tamilakaranja.github.io/Week-2-project/

---

## Features

- **Sticky navigation bar** with smooth-scroll links, a dark mode button and a cart link
- **Hero section** with a bold call-to-action
- **Shop by Style** category grid (Dresses, Streetwear, Shoes, Accessories)
- **New Arrivals** section
- **Product showcase** built with CSS Grid (8 products with category, name, price and rating stars)
- **Filter and sort controls** (UI only)
- **Product detail modals** opened with the CSS `:target` selector (no JavaScript)
- **Static cart sidebar** with sample items and a total
- **Dark mode** toggle using a hidden checkbox and the `:has()` selector
- **Fully responsive** layout with breakpoints for tablets and small phones
- **CSS custom properties** (variables) for the colour palette, spacing, radius and transitions

---

## Tech Stack

| Technology | Use |
|------------|-----|
| HTML5 | Semantic page structure |
| CSS3 | Grid, Flexbox, variables, transitions, media queries, `:target`, `:has()` |
| GitHub Pages | Hosting |

---

## Project Structure

```
Week-2-project/
├── index.html      # Page markup (navbar, hero, shop, modals, cart, footer)
├── style.css       # All styling, including dark mode and responsive rules
├── photos/         # Product and category images
└── README.md
```

---

## Getting Started

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/tamilakaranja/Week-2-project.git
   ```
2. Open the folder in **VS Code**.
3. Open `index.html` in your browser, or use the **Live Server** extension (right-click `index.html` → *Open with Live Server*).

No build tools or dependencies are needed.

---

## Design System

### Colour palette

| Variable | Hex | Use |
|----------|-----|-----|
| `--primary` | `#9b5de5` | Accents and labels |
| `--pink` | `#f15bb5` | Highlights and hover states |
| `--dark-pink` | `#d83b99` | Buttons |
| `--dark-purple` | `#190f2c` | Navbar, about section, footer |
| `--purple` | `#241334` | Hero gradient |
| `--light-purplebg` | `#e2c9f3` | Page background |
| `--white` | `#ffffff` | Cards and text on dark |

## How It Works

- **Modals:** each "Add to Cart" link points to a modal ID (e.g. `#product1`). The CSS `:target` selector displays the matching modal, and the close button links back to `#shop`.
- **Dark mode:** a hidden checkbox (`#dark-mode-toggle`) is toggled by a label. CSS uses `body:has(#dark-mode-toggle:checked)` to restyle the page.
- **Cart:** a static section at `#cart` that shows sample items. It is a visual mockup only.

---

## Future Improvements

- Add JavaScript for working filter, sort and cart logic
- Save the cart and dark mode preference with `localStorage`
- Add a print stylesheet
- Add a checkout flow

---

## Author

Tamila Karanja ~ Founder Nairobi, Kenya

Built as a Week 2 project.

---

