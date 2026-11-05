# CHALLENGE 02 — Golden Ticket 🎟️

**Level:** Beginner  
**Suggested time:** 2–3 hours (basic ticket: around 90 minutes)  
**Tech:** HTML5 + CSS3 ONLY  
**Goal:** Recreate a stylish, fictional music festival ticket from the provided reference screenshots.

## Your mission

The fictional festival **TINY NOISE** needs a digital ticket. Create **one attractive ticket component** — **not a full landing page** — using just HTML and CSS. Your design should look like a real event pass, but the ticket and barcode are decorative, not valid for entry.

You can use the screenshots in `references/` to understand the expected design. **The student ZIP contains no finished solution.**

## Required content

The design has a short page intro and one big ticket:

**Page intro**
- Logo / tiny label: `✳ paperplay.`
- Challenge label: `SMALL BUILDS / NO. 02`
- Headline: `Good times, admit one.`
- Description: `One tiny ticket. One ridiculously good night. Absolutely zero boring vibes.`

**Left side of ticket (coral)**
- Tiny overline: `AN EXTREMELY IMPORTANT EVENT` / `VOL. 001 / 2027`
- Small overline: `WELCOME TO THE VERY FIRST`
- Huge title: `TINY NOISE.`
- Funny subtitle: `Music for people who dance in grocery stores.`
- Bottom labels: `LIVE & LOCAL & VERY LOUD` / `ALL AGES, ALL GOOD VIBES`

**Right side of ticket (cream)**
- Heading: `OFFICIAL ENTRY PASS` / `ADMIT ONE`
- `DATE` — `14 MAY 2027`
- `DOORS OPEN` — `6:30 PM`
- `VENUE` — `THE BACKYARD STAGE`
- `ACCESS` — `GENERAL ADMISSION`
- Ticket number: `TN-2027-0042`

## Color palette

| Purpose | Hex |
| --- | --- |
| Page background | `#F7F0DF` |
| Dark text / border | `#302340` |
| Coral poster panel | `#FF7959` |
| Bright yellow accent | `#FFDF69` |
| Ticket stub paper | `#FFFAF0` |
| Muted small labels | `#776B7B` |

## Base requirements

1. Use **semantic HTML** with `header`, `main`, `article`, `section` where appropriate.
2. Save the markup in `index.html` and styles in `style.css`.
3. Create a centered page intro with heading and subtitle.
4. Make a large ticket with **two columns** on desktop.
5. Style the left panel with coral background and bold typography.
6. Style the right panel with readable event details.
7. Separate the panels with a **dashed line** like a real ticket stub.
8. Style typography, margins, padding, border radius and shadow.
9. On narrow screens, the two ticket panels must **stack vertically** without horizontal scrolling.
10. **No JavaScript, libraries, frameworks or externally hosted assets**.

## Optional bonus points ⭐

- Make a yellow smiley face using circles and CSS, with no image.
- Draw a fake decorative barcode with `repeating-linear-gradient()`.
- Make ticket edge notches with small circle elements.
- Give the ticket a subtle hover lift effect.
- Add visible keyboard focus styling to the logo link.
- Make your own festival name, date and colors.

> Remember: The barcode is only a graphic pattern. You do **not** need to generate a real QR code, scannable barcode, or booking system.

## Suggested 3-stage workflow

**Stage 1 — 30 min:** Write the HTML: header, intro, ticket sections and details. Check content in the browser.

**Stage 2 — 60 min:** Create the desktop ticket, backgrounds, borders, typography and spacing. Use Flexbox or CSS Grid.

**Stage 3 — 30–60 min:** Make the layout responsive and add optional decorative details.

## Submission checklist

- [ ] Page intro, headline and description are present.
- [ ] Ticket left and right panels contain the required content.
- [ ] Two distinct ticket panel backgrounds.
- [ ] Clear hierarchy: big festival name, medium section heading, small details.
- [ ] Dotted/dashed dividing line between ticket sections.
- [ ] Ticket is readable at desktop and phone sizes.
- [ ] No unwanted sideways scrolling on small phones.
- [ ] HTML and CSS files are separate; no JavaScript used.

## What to submit

A folder (or ZIP) with `index.html`, `style.css`, and optionally your own local image assets. A screenshot of the result is also helpful.

**Note for mentors:** The reference shows some *bonus* CSS decorations. A correct basic ticket with good spacing, responsive layout and readable content is a successful submission even if it does not reproduce every decorative star or smiley.
