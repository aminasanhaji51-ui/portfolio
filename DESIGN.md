# Design

Classic consultant landing page, one column of 1160px max, white ground.

## Colour
- Ground `#ffffff`, alternate band `#f4f6f5`, ink `#10201c`, text `#3d4a46`, muted `#62706b`, lines `#e2e7e5` / `#c9d2cf`.
- Brand: pine green `#12493f` (CTA, monogram, method band), tint `#e6efec`. Success dot `#1d7a55`.
- Dark theme mirrors every token (ground `#0f1715`, brand `#5cb39c`).
- Strategy: restrained, with one full-width brand band (Méthode) for rhythm.

## Type
- Display: Schibsted Grotesk 600 (headings, numbers), tracking -0.02 to -0.025em.
- Body: Hanken Grotesk 400/500/600, 17px / 1.6.

## Components
- Buttons: 48px, radius 6px; primary pine, secondary outlined.
- Cards (services, case studies, contact form): white, 1px line, radius 10px, no shadow.
- Lists with hairline rules for pains, timeline, other missions, FAQ (`<details>`).
- Status dot + label for mission state (En production / Mission terminée).

## Rhythm
Sections 96px (64px on mobile), headings 48px above content, side gutter 20–32px.

## Behaviour
- Sticky header gains a hairline after scroll; CTA shortens to « Contact » under 560px.
- Contact form posts to Netlify Forms via fetch, with inline validation, success and error messages, honeypot, and `/merci.html` as no-JS fallback.
