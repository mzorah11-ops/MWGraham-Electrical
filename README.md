# M W Graham Electrical Limited

One-page website for M W Graham Electrical Limited, commercial and industrial electricians in Milton Keynes.

**Live:** https://mzorah11-ops.github.io/MWGraham-Electrical/

Plain HTML, CSS and JavaScript in a single `index.html`. No build step and no dependencies.

## Run locally

```
node serve.mjs
```

Then open http://localhost:8084/ (set `PORT` to use another port).

## Things to fill in

Open `index.html` and look for the `SETTINGS` block at the top of the main script.

- **Contact details:** `phone`, `email`, `whatsapp`, `address` and `hours`. Anything left empty stays hidden. Filling one in switches on the matching call, email, WhatsApp, address and opening-hours slots across the site, including the survey form's send buttons and the mobile call bar.
- **Reviews:** add real customer reviews to `reviews.json` (see `reviews.template.json` for the format). Until then the Testimonials section shows clearly labelled sample cards.
- **Photos:** project photos live in `images/`; the list is in the `PHOTOS` array in the same script.

Publishing is automatic: every push to `main` rebuilds the live site in about a minute.
