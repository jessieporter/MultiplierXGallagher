# Gallagher × Multiplier — Global EOR Proposal Microsite

A single-file HTML microsite built for Multiplier to support their EOR evaluation with Gallagher Group Limited. The site is designed to demonstrate deep country expertise and service differentiation — without naming competitors directly.

---

## Files

| File | Description |
|------|-------------|
| `gallagher-multiplier-eor.html` | The complete microsite — self-contained, no dependencies except Google Fonts |
| `README.md` | This file |

---

## How to Use

1. **Open locally** — double-click `gallagher-multiplier-eor.html` in any browser. No server required.
2. **Share as a link** — host on any static file host (e.g. Netlify Drop, GitHub Pages, Google Drive "anyone with link") and send the URL to your Gallagher contact.
3. **Send as attachment** — the file is fully self-contained and can be emailed directly.

---

## Booking Link

Jessie's calendar link appears in **10 places** across the site:
- Sticky nav bar (always visible)
- Hero section (primary CTA)
- Banner below the hero
- Inside the "Why Multiplier" comparison section
- Bottom of every country tab (5 country-specific callouts)
- Footer CTA section

**To update the booking link**, find and replace all instances of:
```
https://calendar.app.google/emFv6Dgq4NQWddDM7
```
with the new URL. There are 10 occurrences — use your editor's Find & Replace (Cmd+H / Ctrl+H).

---

## Countries Covered

| Country | Payroll | 13th Month | 14th Month | Notice Period |
|---------|---------|-----------|-----------|---------------|
| 🇨🇴 Colombia | Semi-monthly | ✓ Primas (mandatory) | ✗ | 30 days (15 for performance) |
| 🇦🇪 UAE (Dubai) | Monthly | ⚡ Customary | ⚡ Customary | 30–90 days |
| 🇲🇽 Mexico | Semi-monthly | ✓ Aguinaldo (mandatory) | ✗ statutory | 30 days |
| 🇰🇪 Kenya | Monthly | ✗ statutory | ✗ | Up to 28 days |
| 🇵🇪 Peru | Monthly | ✓ July bonus (mandatory) | ✓ December bonus (mandatory) | 30 days |

---

## Site Structure

```
├── Sticky Navigation          — Gallagher orange bar, logo, booking CTA
├── Hero                       — Headline, subtext, primary CTAs
├── Jessie Booking Banner      — Dedicated scheduling callout
├── Why Multiplier             — 5-row comparison vs. typical EOR platforms
│   ├── Customer Support       — 24/7 humans vs. chatbots/tickets
│   ├── Account Management     — Named CSM vs. shared/rotating teams
│   ├── Pricing Model          — Transparent pricing vs. hidden fees
│   ├── Total Cost of Ownership — Owned entities vs. partner networks
│   └── Compliance & IP Risk   — Multiplier holds risk vs. client exposure
├── Platform Overview          — Entity model, industries, headcount, portal
├── Country Tabs (5)
│   ├── Quick Facts Bar        — Notice period, payroll cycle, 13th/14th month
│   ├── Statutory Requirements — 6 deep-dive items per country
│   ├── Pricing & Fees         — EOR fee, payroll, termination
│   ├── Payroll & Compliance   — Frequency, tax filings, contributions
│   ├── Benefits & Onboarding  — Mandatory benefits, onboarding time, support
│   └── Jessie Strip           — Country-specific booking CTA
└── Footer                     — Full Jessie CTA + legal disclaimer
```

---

## Branding

- **Primary color:** Gallagher Orange `#F47920`
- **Dark/black:** `#111111`
- **Fonts:** Barlow Condensed (headings) + Barlow (body) via Google Fonts
- **Multiplier accent:** Green `#00A87A` (used for ✓ checkmarks and $0 setup fee)

---

## Customisation Notes

| What to change | Where to find it |
|---------------|-----------------|
| Booking link | Find & replace `calendar.app.google/emFv6Dgq4NQWddDM7` |
| Jessie's name/title | Search `Jessie` — appears in avatar initials and footer title |
| EOR fee ($600) | Search `$600` |
| Country statutory data | Each `<div class="statutory">` block per country section |
| Brand colors | CSS variables at top of `<style>` block (`--orange`, `--black`, etc.) |

---

## Disclaimer

Country statutory information is provided for guidance purposes only and does not constitute legal advice. Pricing and terms are subject to change. Contact your Multiplier representative for a binding proposal.
