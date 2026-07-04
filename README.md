# Beanstalk — Landing Site (client demo)

Live static landing page + funnel front-end for **Beanstalk**, edible-garden design and
installs for young families in Richmond, Delta and Surrey, BC.

Served via GitHub Pages. This repo contains **only the public website** (no business
strategy, pricing, or deal documents).

## Pages
- `index.html` — the landing page (hero, how-it-works, before/after slider, founder, FAQ, lead form)
- `thank-you.html` — post-submit confirmation
- `privacy.html`, `terms.html` — legal
- `assets/` — imagery

## Demo notes (before real launch)
- **Imagery is AI-generated** placeholder photography. Replace with real install/family
  photos, and do not present the AI people (including the founder portrait) as real clients.
- **The lead form is a demo:** it validates and forwards to `thank-you.html`. Wire a real
  form (Tally) + backend (n8n → Airtable/Cal.com) to actually capture and book leads.
- **Meta Pixel** is dormant until a real Pixel ID replaces the `{{META_PIXEL_ID}}` placeholder.
- Register `beanstalkgardens.ca`, add the real business name + mailing address (CASL), and
  confirm pricing before going to production.
