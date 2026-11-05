# Challenge 04 — Join the Happy Club! 🎨

**Level:** Beginner (with some Flexbox practice)  
**Time:** 2–3 hours  
**Tech:** HTML5 and CSS3 only — no JavaScript, Bootstrap, Tailwind, or React

## Mission

A tiny, fictional creative club needs a brand-new registration form. Your job is to reproduce the supplied **desktop and mobile reference screenshots** as closely as you can, using the starter files and included illustration.

This is a **single form screen**, not a full website or working authentication system. The starter includes semantic form controls, but not the finished visual solution. Your task is primarily HTML comprehension and CSS styling; advanced students can recreate the HTML themselves.

## What you have

- `index.html` — unfinished HTML starter
- `style.css` — color tokens and CSS TODO comments
- `assets/club-card.svg` — ready-made decorative artwork; you do **not** need to draw it
- `references/reference-desktop.png` — desktop design (1440px)
- `references/reference-mobile.png` — phone design (390px)
- `references/reference-small-mobile.png` — narrow phone (320px), bonus reference

## Required content

**Left panel**
- Club logo: `the happy club.`
- Main heading: `Find your kind of weird.`
- Description: `A cozy club for the curious, the creative, and the people who wave at dogs.`
- Supplied membership-card illustration

**Right panel**
- Title: `Well, hello there! 👋`
- Subtitle: `Fill this in and consider yourself officially delightful.`
- First name — required text input
- Last name — required text input
- Email address — required email input
- Password — required password input, **at least 8 characters**
- "What makes you happy?" — required `<select>` with a placeholder and four options:
  - Making stuff & being creative
  - Games & geeky adventures
  - Snacks, coffee & good food
  - A little bit of everything
- "Choose your vibe" — one required choice from **Chill / Chaotic / Sunshine** (radio buttons)
- Promise checkbox — required: `I promise to bring good vibes and respect the other club members.`
- Submit button: `Join the happy club ↗`
- Disclaimer: `This is a practice form. Your personal info is not sent anywhere.`

## Skills to practice

1. Semantic structure: `<header>`, `<main>`, `<section>`, `<form>`, `<footer>`
2. `label` + `for` matching an input's `id`
3. Input types `text`, `email`, `password`, `radio`, `checkbox`
4. Native browser validation: `required`, `type="email"`, `minlength="8"`
5. Select menu with an empty, disabled, initially selected placeholder option
6. Flexbox, CSS Grid, margins, padding, borders and border-radius
7. `:hover`, `:focus` / `:focus-visible` and `:checked` styles
8. Media queries to stack the two panels on phones

## Suggested build order

1. Read the semantic HTML and test all the supplied labels, inputs and native validation. Optional: rebuild them yourself for extra practice.
2. Extend the supplied starter CSS. The form is usable, but its visual layout is intentionally unfinished.
3. Position the two desktop panels, then style the left illustration.
4. Style input controls, dropdown, radio tiles, checkbox, and primary button.
5. Test built-in browser validation with missing values, an invalid email and a short password.
6. Make the layout responsive; ensure no horizontal scrollbar at 390px and 320px.
7. Compare against both reference screenshots and polish spacing.

## Important: this is a demo, NOT a real signup service

The starter already uses `<form action="welcome.html" method="get">`, and the `welcome.html` page is included. **Do not put `name` attributes on the first name, last name, email or password inputs**, because those values would then be exposed in the URL. Radio inputs must share `name="vibe"` to behave as a group; that harmless preference may appear in the URL. No user account is created; no personal data should be sent to any backend.

## Submission checklist

- [ ] Form uses correct native HTML elements and valid labels
- [ ] Every required field is validated in the browser
- [ ] Radio buttons allow selecting only one option
- [ ] Focused input has a clearly visible focus style
- [ ] Layout looks similar to the desktop reference
- [ ] Mobile view is readable without sideways scrolling
- [ ] No JavaScript or UI framework
- [ ] Both `index.html` and `style.css` are submitted

## Bonus (optional)

- Add a gentle hover lift on the submit button.
- Make the selected radio tile change color using `:checked`.
- Add a friendly success message style to `welcome.html`.
- Improve keyboard focus for every interactive element.

## Evaluation (100 points)

| Category | Points |
| --- | ---: |
| Correct HTML + accessible labels | 25 |
| Functional HTML form + validation | 35 |
| Visual accuracy, colors, and spacing | 25 |
| Mobile layout and focus states | 15 |

Have fun, and remember: a nice form is more than pretty CSS — it should be **usable**.
