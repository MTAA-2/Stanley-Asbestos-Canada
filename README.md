# Asbestos / Lung Cancer Claims — Stanley Law

Static GitHub Pages landing page (HTML + CSS only, no PHP) modeled on
https://www.asbestosjusticehelp.com/, built on the user's uploaded
framework files index-10.html / style-12.css (his published Massachusetts
Tobacco page at majusticehelp.com).

## Files

- `index.html` — the page
- `css/style.css` — all styling

## Framework carried over from the upload (unchanged)

- MTAA CIPA block script
- Meta Pixel 1238664640565416 (with ViewContent track)
- **Form embed nf_3270a8a1b0e4425cb70e9f97f2fa5a3c** — the new embed from
  the uploaded framework (changed from nf_14bb49f... in his edit)
- Overflow form card: hangs past the hero and scrolls internally
  (`overflow: auto`); his `.section-parallax-law` light band and his
  mobile values are retained
- Footer legal links are his relative `privacy-policy.html` /
  `disclaimer.html` (as in the uploaded framework)

## Branding — one flag

The sample displays **no firm name, logo, address, or phone** on the
landing page itself. The only firm name anywhere on it is **Stanley Law**,
in the form consent text — so branding was converted to Stanley Law
(text logo in the header, sponsor line, © line). The page is phoneless,
matching the rendered sample.

**Flag:** the sample's Disclaimer / Privacy Policy links point to a
*different* site (asbestosclaimshelp.com) whose pages name a different
firm, **Napoli Shkolnik Canada** (Alberta law). If the sponsor should be
Napoli Shkolnik Canada rather than Stanley Law, say the word and the
name swaps in the header, disclaimer, and © line.

## Palette (sampled live from asbestosjusticehelp.com, 2026-11-11)

- Dark teal #134D59 — top bar, titles, hero gradient start
- Teal #365B6F — hero gradient mid, cards-section parallax overlay
- Black #000000 — hero gradient end; hero parallax overlay (his value)
- Charcoal #30373E — footer (sample's form-header tone)
- Mid grey #A2A2A2 — header gradient start (his gradient, recolored)
- Red #D50001 — accents and qualifier checks
- Yellow #DCC82B — CTA buttons (dark text), highlights; hover #EFEE5A
- Light grey #EFEFEF — band
- Headlines switched from the framework's serif to the sample's bold
  sans-serif (Inter/Arial) throughout

CSS is identical to the uploaded style-12.css except color values,
heading font-family values, and the three parallax image URLs, which are
placeholders (verified by diff).

## Content (from the sample)

- Hero: "Lung Cancer Claims. You Might Be Entitled to Compensation." —
  diagnosed with lung cancer, throat cancer, COPD, or mesothelioma;
  current/former smokers may still qualify
- Know the Risks: how asbestos exposure happens (workplace materials and
  insulation, pre-1980s homes/renovations, secondhand via clothing);
  Canada context
- Cancers linked: mesothelioma, lung, throat, colon, laryngeal,
  pharyngeal, esophageal, ovarian, stomach cancers, COPD/emphysema
  (the sample does not mention asbestosis, so it is not included)
- Exposure cards from the sample's trades/industries (construction,
  insulation/pipe, electrical/sheet metal, shipbuilding, iron/steel and
  manufacturing, power plants/mining, automotive, firefighting,
  secondhand)
- Trust funds band (the framework's light parallax "law" section):
  U.S.-based trusts, some available to Canadians; no dollar figures —
  the sample states none
- FAQs built from the sample's content (smokers qualify; what the form
  asks — including province and existing-attorney questions; exposure in
  Canada; compensation sources; contingency terms)
- Disclaimer: the sample's attorney-advertising text verbatim

## Placeholders to replace

- `images/REPLACE-WORKER-IMAGE.jpg` — side image (worker photo)
- `YOUR-IMAGE-URL-HERE` — hero parallax background
- `YOUR-IMAGE-URL-HERE-2` — exposure-cards parallax background
- `YOUR-IMAGE-URL-HERE-3` — trust-funds (law) parallax background
