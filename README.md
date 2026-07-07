# Saahvik — Premium Website Template Ecosystem

A growing collection of premium, production-ready website templates for the accommodation and hospitality industry — hostels, PGs, co-living spaces, boutique hotels, resorts, villas, homestays and more — plus the marketplace that showcases them.

**Live structure**

```
index.html                      → Saahvik marketplace (catalog, tiers, process, contact)
templates/
  urbannest/index.html          → ★★★   Boys hostel / student accommodation · single-page
  vedika/index.html             → ★★★   Girls hostel & PG · single-page
  commonwealth/index.html       → ★★★★  Co-living community · single-page · dark/light theme
  meridian/                     → ★★★★  Boutique hotel · multi-page
    index.html                  →        Home
    rooms.html                  →        Rooms & suites with tariffs
    reservations.html           →        Reservation request flow
    style.css                   →        Shared design system for the template
  serai/index.html              → ★★★★★ Luxury desert resort · immersive single-page
```

## Design principles

Every template in the catalog follows the same non-negotiables:

- **A unique identity** — its own typography pairing, colour system, layout language, motion style and copywriting voice. No recolours, no repeated layouts.
- **Real content** — complete, realistic copy for a plausible client. No lorem ipsum, no unfinished sections.
- **Conversion-first UX** — every page funnels to an enquiry: WhatsApp deep links with pre-filled messages, click-to-call, and enquiry forms that compose a WhatsApp message from the visitor's answers.
- **Zero build step** — plain HTML/CSS/JS. Any page can be opened directly in a browser, dropped onto any static host, and edited by hand.
- **Self-contained visuals** — art direction is done with gradients, CSS scenes and SVG-free compositions so demos never ship broken image links; client photography slots in at customisation time.
- **Accessible & responsive** — semantic markup, labelled forms, `prefers-reduced-motion` support, and mobile-first layouts throughout.
- **SEO-ready** — meaningful titles, meta descriptions and heading structure on every page.

## Quality tiers

| Tier | Name | What it adds |
|------|------|--------------|
| ★ | Launch | Clean, fast, conversion-focused essentials |
| ★★ | Presence | Stronger branding, galleries, reviews |
| ★★★ | Signature | Distinct art direction, smooth motion, booking-oriented UX |
| ★★★★ | Prestige | Editorial layouts, advanced interaction, multi-page architecture, theming |
| ★★★★★ | Flagship | Immersive scroll experiences, cinematic pacing, bespoke-level detail |

The catalog targets **100 templates**, each star level shipping in single-page and multi-page variants. The five templates above are the first entries and set the quality bar; new templates are added to `templates/<slug>/` and registered as a card in the marketplace catalog in `index.html`.

## Adding a new template

1. Create `templates/<slug>/index.html` (plus extra pages and a shared `style.css` for multi-page templates).
2. Give it a distinct identity: new font pairing, palette, layout system and copy voice.
3. Wire every CTA to WhatsApp (`https://wa.me/919530301131`) with a template-specific pre-filled message, plus `tel:` and `mailto:` links.
4. Credit the footer: `Website by Saahvik · Template: <Name> <stars>`.
5. Add a catalog card in `index.html` with tier, category filter tags, feature chips, and Live Demo / Enquire actions.

## Contact

- **Website:** [www.saahvik.com](https://www.saahvik.com)
- **Email:** [websitecontact@saahvik.com](mailto:websitecontact@saahvik.com)
- **Phone / WhatsApp:** +91 95303 01131

© Saahvik. All templates are original works.
