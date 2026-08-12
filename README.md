# King of Kings Drywall — Demo Website

A single-page demo site for **King of Kings Drywall**, an owner-run drywall repair, finishing and texture-matching crew in Tampa, FL. Part of the Wilson's Websites demo-first pitch workflow (build first, then share the link).

## The business
- **Name:** King of Kings Drywall
- **Location:** 1718 W Powhatan Ave, Tampa, FL 33603 (serves Tampa & Hillsborough County)
- **Phone / text:** (805) 263-8641 → `tel:+18052638641` / `sms:+18052638641`
- **Hours:** GBP lists 6 AM–11 PM, 7 days (solo-operator anomaly) — **softened** on the site to "Open 7 days a week · early & evening appointments." No literal hours table; hours omitted from JSON-LD.
- **Google:** 5.0 ★ (219 reviews — exceptional volume)
- **Owner / crew:** Dennis (inspection + coordination, on every job); installers David & Eric; a finisher whose spackle work reviewers praise
- **Known for:** texture-matched hole repair after plumbing/electrical work, taping & covering the work area, tidy cleanup, fair pricing, 8-year repeat landlord customer
- **Phone note:** 805 area code (CA cell, owner transplant) but address/zip = Hillsborough County (in-territory, verified). Phone + address MATCHED Google Places.
- **No existing website.**

## Design (Tier 1 — Clean Slate)
- **Fonts (pre-assigned, Google):** display **Germania One** (regal blackletter — fits the "King of Kings" name; used for brand, headings, stat numbers only) + body **Average** (readable transitional serif). Used only via the assigned pair.
- **Palette "drywall-white + plaster-grey with royal-blue trust accent":** page plaster `#f2efe8`, alt band `#faf8f3`, paper `#fff`; royal blue `#1f3f96` / deep `#152c68` / ink `#0f1c40`; regal gold accent `#c9a12f` / soft `#dcb84f` (crown mark + stars only); plaster-grey muted `#586074`.
- **Layout:** sticky header (call CTA flush right, hamburger mobile nav), full-bleed hero over a freshly-finished drywall room with slow Ken Burns settle, six-cell royal trust strip, four value cards, four service cards, an owner/story band (branded van photo), a **testimonial-forward** reviews section (large pull-quote + six real Google reviews — the star, leaning on the 219-review social proof), a recent-work photo strip, a service-area/contact band (call + text + based-in + hours), and a royal-blue CTA band.
- Finalized Tier-1 polish: full above-the-fold hero stack (eyebrow → headline → sub → CTA pair → glass trust chip 5.0★/219), one-shot blur+scale scroll reveals (rootMargin bottom +12% pre-trigger + momentum safety sweep), layered soft shadows, hairline borders, sheen-sweep on the primary CTA, alternating plaster/plaster-tint bands.
- All motion gated behind `prefers-reduced-motion`. No fixed/sticky bottom mobile call bar (header call CTA is the persistent contact affordance).

## Images (all the business's own Google Business Profile photos — real King of Kings jobs)
No stock used. All 11 images are genuine work photos from the King of Kings Drywall GBP listing, downloaded via Places API and PIL re-encoded (progressive JPEG, ≤350 KB), each visually reviewed against its alt text. Because every image is the business's own work, there is zero Unsplash-collision exposure.

- `hero.jpg` / `og-preview.jpg` — a freshly hung, taped & floated room with a tray ceiling (own listing photo).
- `owner.jpg` — Dennis beside the King of Kings work van, lettered "Repair · Finishing · Texture · (805) 263-8641" (the one photo attributed to King of Kings directly).
- `svc-repair.jpg` — bathroom wall with drywall access holes prepped for patching.
- `svc-ceiling.jpg` — ceiling opened to the joists after water damage.
- `svc-texture.jpg` — finished knockdown-textured ceiling, painted.
- `svc-finish.jpg` — whole room drywalled & textured, ready for primer.
- `work-1.jpg` — knockdown texture being applied to a wall.
- `work-2.jpg` — water-damaged ceiling before repair.
- `work-3.jpg` — texture spray in progress over draped/protected furniture.
- `work-4.jpg` — bathroom taken to the studs, prepped for new drywall.

## Reviews used (real Google reviews, first name + last initial)
- **Vincent J.** — professional, timely, clean; Dennis clear communication; David taped/covered, pro-level, clean.
- **Stephen S.** — texture-matched a large amount of drywall holes after a plumbing project; David & Eric on time, on schedule; Dennis coordinated.
- **Gina B.** — showed up the day after calling, thorough inspection, reasonable price, next-day re-inspection; "his brother was an artist with the spackle… like there were never holes there" (used as the pull quote).
- **Rob P.** — engineer, landlord, 8 years of use, never a touch-up needed ("done to perfection").
- **Luis G.** — fast, reliable, fair pricing, outstanding quality, attention to detail.

## Facts deliberately left out (not verifiable / softened)
- No founding year, license number, or email (none published).
- Literal 6 AM–11 PM hours softened to "open 7 days · early & evening appointments" per the solo-operator anomaly.
- "General Contractor" GBP primary type not used in copy — reviews are pure drywall, so the site is drywall-scoped.
