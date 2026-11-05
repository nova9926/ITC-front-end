# Challenge 05 — Tiny Bites Menu 🍓

**Difficulty:** Beginner / Easy  ·  **Time:** 2–3 hours  ·  **Stack:** HTML5 + CSS3 only

## The mission

Recreate the **Tiny Bites** mini café menu from `references/reference-desktop.png` and make it adapt to `reference-mobile.png`. This is a **single menu screen with a small intro**, not a complete e-commerce website. Your goal is to practise **CSS Grid, reusable cards, spacing, text hierarchy, and media queries**.

## Required page parts

1. A small green announcement strip, café name/logo, and two menu links.
2. A friendly heading: **Small bites. Big happy.** and one short introduction.
3. **Six food cards**. Each card contains a local SVG illustration, a category label, a food name, a short description, and the price in Algerian dinars.
4. A mint-green **lunch deal** banner: any toast + any drink saves 150 DA.
5. A simple footer.

## Use these exact food items

| Illustration | Name | Category | Price | Description |
|---|---|---|---|---|
| `assets/pancakes.svg` | Berry Happy Pancakes | SWEET & FLUFFY | 780 DA | Three fluffy clouds with fresh berries and a big hug of syrup. |
| `assets/toast.svg` | Good Morning Toast | SAVOURY & CRUNCHY | 650 DA | Crunchy toast, creamy avo, and a sunny little egg. |
| `assets/croissant.svg` | Sunshine Croissant | GOLDEN & BUTTERY | 390 DA | Flaky, buttery, and basically a warm morning in a bite. |
| `assets/strawberry-soda.svg` | Pink Fizz Lemonade | SIP & SMILE | 430 DA | Strawberry bubbles, lemon zing, and pure summer energy. |
| `assets/matcha.svg` | Cloud Nine Matcha | COZY & CREAMY | 520 DA | A little green magic with the softest milky cloud on top. |
| `assets/cookie.svg` | Chunky Choco Cookie | BAKED WITH LOVE | 290 DA | Crispy edges, gooey middle, and a lot of chocolate. |

## Suggested color palette

- Page cream: `#FFFBF3`
- Dark green text: `#263A36`
- Coral accent: `#FF8069`
- Mint banner: `#BCDCCB`
- Pink accent: `#FAD2D9`
- Yellow accent: `#FFE29A`
- Card backgrounds: white

## Essential CSS practice

- `display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px;` for menu cards.
- `display: flex` for food names + prices on the same row.
- `border-radius`, `padding`, `box-shadow`, `:hover` for visual polish.
- `@media (max-width: 980px)` to switch to **two columns**.
- `@media (max-width: 650px)` to switch to **one column**.
- `object-fit: contain` to display every SVG illustration without cropping.

## Rules

- HTML5 + CSS3 **only**; no JavaScript, Bootstrap, Tailwind, React or component libraries.
- All food illustrations are supplied in `assets/` and work **offline**.
- Images need meaningful `alt` text; use a real `<h1>` and `<h2>` headings.
- Navigation links should lead to actual page sections using anchor IDs.
- No horizontal scrolling on mobile.
- The lunch-deal link is only a demo anchor, not a real purchase flow.

## Suggested order of work

1. **30 min:** Write semantic HTML structure for the introduction, menu, and offer.
2. **45 min:** Style headings, colors, the card structure, and 3-column Grid.
3. **30 min:** Add illustrations, prices, shadows, stickers, and spacing.
4. **30 min:** Responsive 2-column and 1-column layouts.
5. **15 min:** Hover states, image accessibility, and final checks.

## Submission checklist

- [ ] All six food items, descriptions, and prices are visible.
- [ ] All six local images load correctly.
- [ ] Cards align in three columns on desktop.
- [ ] Layout becomes two columns on tablet, one on mobile.
- [ ] Special offer banner is present.
- [ ] Readable text, consistent spacing, no clipped items.
- [ ] HTML and CSS are in separate files.

**Bonus:** Add tiny handwritten-looking stickers, CSS-only decorative sparkles, subtle card lift on hover, and an accessible focus outline on navigation links.

## How to run

Open `index.html` directly in your browser. No installation or internet is needed.
