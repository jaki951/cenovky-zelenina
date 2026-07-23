# Cenovky (grocery price tags) — project context

## What this is
Grocery price tags ("cenovky") for a Slovak market/grocery, redesigned from an
original spreadsheet of ~50 fruit/veg items into a single HTML template style
called **Alternatíva 1 "Trhovisko"** (kraft-paper / forest-green market look).

The template is fully built out for one product — **Petržlen (parsley)** — in
`cenovka_alternativa1_petrzlen.html`. It's a single self-contained HTML file:
fonts load from Google Fonts CDN, the product photo is embedded inline as a
base64 JPEG. No build step, no dependencies.

Live version: hosted on GitHub Pages from this repo (`cenovky-zelenina`).

## Design system (locked in — don't change without asking)
- **Card size:** 100mm × 60mm, sharp corners (border-radius:0, no box-shadow
  on the outer `.tag`) so it cuts cleanly for print.
- **Palette:** kraft/cream background, dark forest-green header band, cream
  text on the band. **No red anywhere in background** — red is reserved for sale/discount
  items only, not used in this base template.
- **Price:** black text (#000) on a white rounded chip, NOT colored.
  Font: **Space Grotesk**, weight 700.
- **Product name:** cream text on the dark green band. Font: **Oswald
- EB Garamond
https://fonts.google.com/specimen/EB+Garamond
Playpen Sans Deva 
Libre Baskerville 
Gluten
merienda
amita**,
  weight 600, upright (not italic), letter-spacing .02em.
  (History: went through Fraunces italic → Fraunces upright → Playfair
  Display italic → DM Serif Display → Oswald. Serif options kept getting
  flagged as either illegible or too stiff; Oswald.)
- **Photo:** circular crop, ring border via `inset box-shadow`, sits behind
  the price chip and quality stamp. Source photos in the original spreadsheet
  are black-and-white line-art style; when colorizing, use a duotone
  approach — for root vegetables like parsley, keep the leafy top green and
  make the root/bulb beige-white (this is the actual natural coloring, not
  arbitrary), with a soft blended transition at the neck, not a hard seam.
- **Quality stamp** ("I. akosť"): small dashed-circle badge, positioned to
  not collide with the enlarged price chip.
- **Origin** (Pôvod): shown as plain text, must stay visible/legible — this
  was a specific requirement, don't let other elements crowd it out.

## Process rules (user preference — important)
- Ask before making any change beyond exactly what was requested — don't
  bundle in "improvements" that weren't asked for.
- The user iterates fast and often in short messages ("try another font",
  "one more time") — when a change is requested without much detail, make a
  concrete, reasonable choice.

## Status / next steps
- Alt1 "Trhovisko" template is finalized and approved for Petržlen.
- **Not yet done:** applying this same template to the remaining ~49
  products from the original spreadsheet (each needs its own product name,
  price, origin, and photo).
- Two other visual directions were explored and rejected: Alt2 "Trhový
  lístok" (red ticket style — rejected, red is reserved for sale items) and
  Alt3 "Zelený trh" (green/gold — rejected, was missing the origin field).
  Don't resurrect these unless asked.
